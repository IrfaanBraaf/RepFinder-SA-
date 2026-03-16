# RepFinder-SA 🇿🇦

RepFinder-SA is a civic technology application that allows South African residents to quickly identify their elected representatives based on their address.

Users simply enter their **South African address**, and the app returns their:

- Ward Councillor
- Member of Parliament (MP)
- Member of the Provincial Legislature (MPL)

Along with key information such as:

- Contact details  
- Political party  
- Electoral region information  

The goal of RepFinder-SA is to improve **civic accessibility and political transparency** by helping citizens easily find and contact the representatives responsible for their area.

---

## Features

- Address-based representative lookup  
- Displays ward councillor, MP, and MPL  
- Shows contact details and political party  
- Mobile and web access  
- Cloud-backed queries using Firebase  
- Simple and accessible civic interface  

---

## Tech Stack

### Frontend
- React (Web)
- React Native (Mobile)

### Backend / Infrastructure
- Firebase Authentication
- Firebase Firestore / Realtime Database
- Firebase Cloud Functions
- Firebase Hosting

---

## Architecture Overview

```
User
  ↓
React / React Native App
  ↓
Address Lookup Logic
  ↓
Firebase Backend
  ↓
Representative Database
```

The application processes a user's address and maps it to electoral boundaries to determine the correct representatives.

---

## Project Structure

```
repfinder-sa/

├── web/                # React web application
├── mobile/             # React Native mobile application
├── firebase/           # Firebase configuration and functions
├── shared/             # Shared utilities and models
└── README.md
```

---

## Use Cases

- Citizens wanting to contact their local representatives  
- Community organisations engaging with government  
- Journalists and researchers  
- Civic education platforms  

---

## Future Enhancements

- Interactive electoral boundary maps  
- Representative performance metrics  
- Issue reporting to representatives  
- Notifications for constituency updates  
- Voting district insights  

---

## License



---

## Vision

RepFinder-SA aims to strengthen democracy in South Africa by making political representation information **accessible, transparent, and easy to use for everyone**.
