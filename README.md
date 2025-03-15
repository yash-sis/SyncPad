# **SyncPad: Real-Time Collaborative Editor**

SyncPad is a **real-time collaborative text editor** built with **Next.js, Liveblocks, and Tailwind CSS**. It allows multiple users to work on the same document simultaneously with seamless syncing and a clean UI.

---

## 🌟 **Features**

- **📄 Live Collaboration** – Edit documents in real time with multiple users.
- **🔑 Authentication** – Secure sign-in with GitHub (via Clerk).
- **📂 Document Management** – Create, delete, and organize your documents.
- **👥 Active Users Indicator** – See who’s editing with live presence updates.
- **💬 Comments** – Discuss and collaborate using inline comments.
- **📢 Notifications** – Stay updated with document activity alerts.
- **📱 Fully Responsive** – Works on all devices, from desktops to mobile.

---

## 🛠️ **Technology Stack**

- **Frontend**: Next.js, TypeScript, Tailwind CSS
- **Realtime Collaboration**: Liveblocks
- **Authentication**: Clerk
- **Editor**: Lexical Editor
- **UI Components**: ShadCN

---

## 🚀 **Getting Started**

### **1️⃣ Clone the Repository**

```sh
git clone https://github.com/yash-sis/SyncPad.git
cd SyncPad
```

### **2️⃣ Install Dependencies**

```sh
npm install
```

### **3️⃣ Set Up Environment Variables**

Create a `.env` file and add:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
```

_(Get API keys from [Clerk](https://clerk.dev/) & [Liveblocks](https://liveblocks.io/))_

### **4️⃣ Run the Development Server**

```sh
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🤝 **Contributing**

Contributions are welcome! Fork the repo, make changes, and submit a pull request.
