

# Simplify

**Simplify** is a modern web app built with Next.js that allows users to manage subscriptions, access wallet features, and view content seamlessly. Users can log in using their phone number and an OTP for secure authentication. Once logged in, they can renew their plans, add balance to their wallet, update their profile, and explore shows.

## Features

- **Phone and OTP Authentication**: Secure login through phone numbers and one-time password (OTP).
- **Plan Renewal**: Users can renew their subscription plans directly from the app.
- **Wallet Access**: The app provides an integrated wallet feature where users can check balances and add funds.
- **Profile Management**: Users can update their personal details such as name and email.
- **View Shows**: Users can browse and view various shows available on the platform.
- **Bottom Navbar**: A bottom navigation bar allows users to easily switch between different sections of the app.

## Tech Stack

- **Framework**: Next.js (React framework for server-side rendering)
- **Styling**: CSS/SCSS or a UI framework like Tailwind CSS/Material UI (depending on your choice)
- **Authentication**: Phone-based OTP authentication system
- **State Management**: React hooks or a global state management library like Redux (optional)
  
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/simplify.git
   ```

2. Install dependencies:
   ```bash
   cd simplify
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add required variables
   ```
   NEXT_PUBLIC_BACKEND_URL=http://localhost:3002
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) to view the app in the browser.

## Features Breakdown

### Authentication (Phone and OTP)

- Users log in using their phone number.
- After entering the phone number, they receive an OTP to their mobile device.
- Once the OTP is verified, the user is logged in, and a session is initiated.

### Renew Plans

- After logging in, users can renew their current subscription plans.
- Plan details are fetched from the API, and users are shown available renewal options.

### Wallet Access and Balance Management

- The wallet page displays the current balance.
- Users can add funds to their wallet through various payment methods.

### Profile Update

- Users can update their profile information such as name and email.
- The profile section allows users to save changes and see their updated details.

### View Shows

- A dedicated section to browse through available shows.
- Users can search and view specific shows.

## Navigation

The app features a **bottom navbar** for easy navigation between different sections. The bottom navbar includes:

- **Home**: Takes users to the homepage, where they can browse shows.
- **Wallet**: Directs users to the wallet section where they can view and add balance.
- **Profile**: Allows users to manage their profile information.
- **Plans**: Allows users to view and renew their plans.

To handle navigation between these sections:

The bottom navbar is always present, allowing users to quickly navigate between key sections of the app.

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a pull request.

## License

This project is licensed under the MIT License.

---
