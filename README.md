##  <a name="table">Table of Contents</a>

1.  [Introduction](#introduction)
2.  [Tech Stack](#tech-stack)
3.  [Features](#features)
4.  [Setup](#setup)

## <a name="introduction"> Introduction</a>

Powered by the latest Next.js and TypeScript technologies, Finan Smart is a sophisticated AI-driven financial advisory tool. It empowers users to manage their finances more effectively by allowing them to input their income, expenses, and budgets, and receive tailored financial advice based on their unique data. Ideal for those eager to explore the integration of AI insights into financial management, this project serves as a practical example of building intelligent, user-focused solutions within a Next.js application.

## <a name="tech-stack"> Tech Stack</a>

- Next.js
- TypeScript
- OpenAI API
- Tailwind CSS

## <a name="features"> Features</a>

**Income and Expense Input**: Allows users to input their income and expenses.

**Budget Management**: Enables users to manage their budgets effectively.

**Personalized Financial Advice**: Provides detailed financial advice based on user-specific financial data using OpenAI's GPT-4 model.

**Responsive Design**: Ensures a seamless experience across different devices.

## <a name="setup"> Setup </a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/Koushik-04KK/FinanSmart.git
cd ai-finance-tracking
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=p
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
NEXT_PUBLIC_OPENAI_API_KEY=

NEXT_PUBLIC_DATABASE_URL=

```

Replace the placeholder values with your actual OpenAI credentials. You can obtain these credentials by signing up on the [OpenAI website](https://openai.com/).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

