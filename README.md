# PeerX - More than just an Alumni portal

## PeerX allows you to connect with peers, find peers on the basis of similar interests in technology, chat with them in real time and conduct mock interviews with peers.

---

# 📚 API Endpoints

Below are the available API endpoints for PeerX backend.

## 🔐 Authentication APIs

| Method | Route | Description |
|:------|:------|:------------|
| POST | `/api/auth/register` | Register a new user |
| POST | `/api/auth/login` | User login and JWT generation |
| GET | `/api/users/profile` | Fetch current user's profile |
| PUT | `/api/users/profile` | Update current user's profile |

---

## 💬 Chat APIs

| Method | Route | Description |
|:------|:------|:------------|
| GET | `/api/messages/:conversationId` | Get all messages in a conversation |
| POST | `/api/messages/:conversationId` | Send a message in a conversation |
| GET | `/api/conversations` | Fetch all conversations for user |
| POST | `/api/conversations` | Create a new conversation (start chat) |

---

## 🎥 Video Call APIs

| Method | Route | Description |
|:------|:------|:------------|
| GET | `/api/call/token` | Get token for initiating WebRTC PeerJS call |
| POST | `/api/call/start/:receiverId` | Notify server about starting a call |
| POST | `/api/call/end/:conversationId` | End a video call and update status |

---

## 🔍 Search APIs

| Method | Route | Description |
|:------|:------|:------------|
| GET | `/api/search/users?query=xyz` | Search users by name, company, skills |
| GET | `/api/search/posts?query=xyz` | Search posts by keywords |

---


