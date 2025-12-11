# Forum

**This is a basic forum that can be extended and customized in many ways to fit your needs.**

## 🌐 Live Demo

**[View Live Site →](https://forum-g9nm.vercel.app/)**

---

## 🛠️ Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/) (App Router)
- **Frontend**: [React 19](https://react.dev/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)
- **Data Fetching**: [TanStack React Query](https://tanstack.com/query)
- **Database**: [MongoDB](https://www.mongodb.com/)
- **UI Components**: [Headless UI](https://headlessui.com/)

---

### Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd Forum
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file in the root directory:

```bash
MONGODB_URI=your_mongodb_connection_string
```

4. Run the development server:

```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

---

## 📝 Environment Variables

Create a `.env` file with the following variables:

| Variable      | Description               | Example                                                        |
| ------------- | ------------------------- | -------------------------------------------------------------- |
| `MONGODB_URI` | MongoDB connection string | `mongodb+srv://user:pass@cluster.mongodb.net/?appName=YourApp` |

---

## 📁 Project Structure

```
src/
├── app/                  # Next.js app router pages
│   ├── api/             # API routes
│   └── post/            # Post detail pages
├── components/          # Reusable components
├── hooks/              # Custom React hooks
├── modules/            # Feature modules
├── services/           # API service layer
├── providers/          # React context providers
├── lib/                # Utility libraries
├── config/             # Configuration files
└── utils/              # Helper functions
```
