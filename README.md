# Title name--BLOCKCHAIN – ENABLED DRUG TRACEABILITY IN HEALTH CARE SUPPLY CHAIN MANAGEMENT
This is a web application that helps trace and verify the authenticity of drugs using blockchain technology. It is built using Django for the backend and Solidity smart contracts deployed on Ethereum (Ganache) using Web3.py.
# Technologies Used
- Django (Python Framework)
- Solidity (Ethereum Smart Contracts)
- Web3.py (Python–Blockchain bridge)
- Ganache (Local Ethereum Blockchain)
- HTML and CSS (Frontend Design)
# Features
- User and Admin login system
- Add and update drug/product details
- Track and view drug traceability status
- Blockchain ensures immutability and transparency
- Smart contract integrated with Web3.py
# Project Structure

DrugTraceability/
├── manage.py
├── DrugTrace/ # Django project settings
├── DrugTraceApp/ # App logic, views, models
│ ├── templates/ # HTML files (Login, Register, etc.)
│ └── static/ # CSS and image files

# How to Run
1. Install dependencies:
   pip install -r requirements.txt
2. Run migrations:
   python manage.py migrate
3. Start server:
   python manage.py runserver
4. Make sure:
   Ganache is running
   Your smart contract is deployed and connected using Web3.py
# About Me
I am Nandini Earla, currently pursuing my M.Tech at BVRIT College of Engineering for Women.
With a strong interest in emerging technologies, I developed this project to explore how blockchain can be used to solve real-world problems like drug traceability. 
This system showcases my ability to work with Django, build and deploy smart contracts using Solidity, and connect blockchain logic to web applications through Web3.py.
I’m passionate about creating secure, scalable, and impactful tech solutions that contribute to the future of digital trust.
# Note
This project is developed for academic and internship purposes.
It runs on a local Ethereum blockchain (Ganache) environment and is intended to demonstrate how blockchain can be integrated with web applications for secure drug traceability.
It can be extended further for deployment on public Ethereum networks or other production-grade blockchains.








