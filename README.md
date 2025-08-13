# Giggle Frontend 🎵 Group project

A React Native mobile application for sharing spare gig tickets within the community. 

Built by **isLoading** team as part of the Northcoders bootcamp final project.

🔗 **Back-end Repository:** [Giggle BE](https://github.com/Andipascale7/giggle-be)

## 📖 About

Giggle connects fellow gig-goers who share your style of outing, no matter how big or small the artist. Share spare tickets among the Giggle user base – strictly no reselling! Just sharing music and art to build community and support local venues.

The app focuses on **free ticket sharing** with **no reselling** and provides an ability to match with people who share the same gig-going style as you.

## ✨ Key Features

### 🎫 Event Discovery & Ticket Management
- **Browse Events**: Scrollable list of upcoming concerts, comedy shows, and local art exhibitions
- **Real-time Search**: Search by keywords with instant results
- **Smart Filtering**: Sort events by date, artist, or location
- **Multi-city Support**: View events happening in different cities
- **Event Integration**: Add new events via Ticketmaster Discovery API

### 🎟️ Ticket Sharing System
- **List Tickets**: Upload spare tickets with seating type and additional notes
- **Find Tickets**: Browse available tickets from other users
- **Status Tracking**: Visual indicators for taken/available tickets
- **No Reselling Policy**: Strictly community-based free sharing

### 👤 User Profiles & Matching
- **Detailed Profiles**: First/last name, username, location, profile picture, and bio
- **Gig Preferences**: Tags for seat preference, singing, moshing, filming style, etc.
- **Profile Compatibility**: Choose ticket sharers based on compatible gig-going styles
- **Editable Profiles**: Users can update their details and preferences

### 💬 Real-time Messaging
- **Instant Chat**: Powered by Socket.IO for live communication
- **Chat Rooms**: Structured messaging system similar to WhatsApp/Messenger
- **Message History**: Persistent conversation storage
- **Active Conversations**: Easy access to ongoing chats

### 🔐 Authentication & Security
- **Secure Registration**: Unique username/email requirements
- **Password Security**: Bcrypt hashing - no plain text storage
- **Login Validation**: Secure password comparison against stored hashes

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm 
- Expo CLI (optional but recommended)
- Access to the Giggle backend API

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Andipascale7/giggle-fe.git
cd giggle-fe
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npx expo start
```

## 📱 Running the App

**Primary Platform**: Android (tailored for Android devices)

- **Expo Go**: Scan QR code with Expo Go app
- **Android Emulator**: Press `a` in terminal
- **Web Browser**: Press `w` in terminal (limited functionality)

## 🏗️ Tech Stack

### Frontend
- **React Native** with Expo
- **TypeScript** for type safety
- **Expo Router** (file-based routing)
- **Socket.IO Client** for real-time messaging



## 🎪 User Journey

1. **Sign Up/Login**: Secure authentication with hashed passwords
2. **Discover Events**: Browse or search for upcoming gigs
3. **List Tickets**: Upload spare tickets with details and notes
4. **Find Tickets**: Search available tickets from other users
5. **Check Profiles**: View ticket holders' gig-going preferences  
6. **Chat**: Message other users about tickets and arrangements
7. **Add Events**: Integrate new events via Ticketmaster API if not in database

## 👥 The Team - isLoading

- [**Andi Pascale**](https://www.linkedin.com/in/andipascale/)
- [**Bethany White**](https://www.linkedin.com/in/bethpwhite/) 
- [**David Potter**](https://www.linkedin.com/in/dg-potter013/)
- [**Leah Stone**](https://www.linkedin.com/in/leah-s-ba9004130/) 
- [**Uzo Ugochukwu**](https://github.com/uzougochukwu)

## 🛠️ Development Challenges Overcome

- Working in agile environment and collaborative Git workflows
- Integrating multiple new technologies (React Native, Socket.IO, MongoDB)
- Implementing real-time communication with Socket.IO
- Managing merge conflicts and team-based development
- Building mobile-first applications with cross-platform considerations

## 🔮 Future Enhancements

- Read receipts for messages
- Typing indicators in chat
- Push notifications
- End-to-end encryption for enhanced security
- iOS optimization and testing

## 📚 Learn More

- [Project Showcase](https://www.northcoders.com/blog/giggle/)
- [Expo Documentation](https://docs.expo.dev/)
- [Socket.IO Documentation](https://socket.io/docs/)
- [Ticketmaster Discovery API](https://developer.ticketmaster.com/products-and-docs/apis/discovery-api/v2/)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

*Building community through music, one shared ticket at a time* 🎸


