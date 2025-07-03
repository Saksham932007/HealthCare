
# CarePlus

**Smarter Healthcare, Simplified**

CarePlus is a modern healthcare appointment management platform that allows patients to connect seamlessly with doctors. Patients can easily search for doctors, book appointments, and receive real-time notifications about their appointment status. Doctors can efficiently manage, approve, or cancel appointments through a user-friendly interface.

Built with **Next.js**, **React**, **TypeScript**, **Appwrite**, and **Sentry**, CarePlus provides a fast, reliable, and secure experience for both patients and healthcare providers.

---

## Features

✅ Patients can book appointments with doctors
✅ Doctors can manage, approve, or cancel appointments
✅ Automatic notifications for approved or canceled appointments
✅ User-friendly and responsive interface
✅ Secure and scalable architecture

---

## Tech Stack

* **Next.js** — for server-side rendering and routing
* **React** — for building reusable and interactive UI components
* **TypeScript** — for type safety and maintainable code
* **Appwrite** — for backend-as-a-service (authentication, database, functions, etc.)
* **Sentry** — for error tracking and monitoring

---

## Getting Started

### Prerequisites

* Node.js >= 16
* npm or yarn

### Installation

```bash
git clone https://github.com/yourusername/careplus.git
cd careplus
npm install
```

### Environment Variables

Create a `.env.local` file in the root directory and configure the following variables:

```env
NEXT_PUBLIC_APPWRITE_ENDPOINT=your_appwrite_endpoint
NEXT_PUBLIC_APPWRITE_PROJECT_ID=your_project_id
NEXT_PUBLIC_APPWRITE_DATABASE_ID=your_database_id
NEXT_PUBLIC_APPWRITE_COLLECTION_ID=your_collection_id
NEXT_PUBLIC_SENTRY_DSN=your_sentry_dsn
```

Replace the placeholders with your actual Appwrite and Sentry configuration.

---

## Running the App

```bash
npm run dev
```

The app will be available at [http://localhost:3000](http://localhost:3000).

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.
For major changes, please open an issue first to discuss what you would like to change.

---

## License

[MIT](LICENSE)

---

## Contact

If you have questions or feature requests, feel free to open an issue or reach out.
