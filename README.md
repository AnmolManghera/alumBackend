# PeerX - More than just an Alumni portal

## PeerX allows you to connect with peers, find peers on the basis of similar interests in technology, chat with them in real time and conduct mock interviews with peers.

---

# 📚 API Endpoints

Below are the available API endpoints for PeerX backend.

## 👤 User APIs

| Method | Route | Description |
|:------|:------|:------------|
| POST | `/user/register` | Register a new user with request body |
| POST | `/user/login` | Login a user and send cookie data |
| GET | `/user/users` | Get all users or filtered users on the basis of query params |
| POST | `/user/sendConnectionRequest` | Send a connection request to another user |
| POST | `/user/acceptConnectionrequest` | Accept a connection request from another user |
| GET | `/user/notifications` | Get notifications for the current user |

---

## 📹 Meeting/Video Call APIs

| Method | Route | Description |
|:------|:------|:------------|
| GET | `/user/schedule` | Get weekly schedule for the current user |
| POST | `/user/updateschedule` | Update weekly availablity schedule for the current user |
| GET | `/user/getusersforinterviews` | Get users available for a mock interview/meeting |
| POST | `/user/requestinterview` | Request another user for a meeting |
| POST | `/user/acceptinterviewrequest` | Accept an interview request from another user |
| GET | `/user/interviews` | Get your scheduled meetings |

---

## 🗨️ Chat APIs

| Method | Route | Description |
|:------|:------|:------------|
| GET | `/chat/my` | Get all chats for the current user |
| POST | `/chat/message` | Send a message to another user |
| GET | `/chat/message/:id` | Get all the messages for the given chat ID |
| GET | `/chat/:id` | Get information about the given chat ID |

---


