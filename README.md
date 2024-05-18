# CollaboLearn

CollaboLearn is an innovative online learning platform designed to facilitate interactive and engaging learning experiences for both instructors and students.

## Features

- **Course Creation**: Instructors can create and publish courses, add video content, quizzes, assignments, and other course materials.
- **User Enrollment**: Students can browse and enroll in courses, track their progress, and interact with instructors and fellow students through discussion forums.
- **Content Management**: Intuitive dashboard for instructors to manage course content and monitor student progress.
- **Payment Integration**: Secure payment system for purchasing courses or subscribing to premium content.
- **Notifications**: Users receive notifications for course updates, new assignments, and announcements.
- **Responsive Design**: Ensure a seamless learning experience across different devices and screen sizes.

## Tech Stack

- **Frontend**: Next.js 13, React, Tailwind CSS
- **Backend**: Node.js with Express.js, Prisma
- **Database**: MySQL
- **User Authentication**: JWT (JSON Web Tokens)
- **Video Streaming**: Mux
- **Payment Integration**: Stripe

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/collabolearn.git

2. Install dependencies:

   ```bash
   cd collabolearn
   npm install
   ```

3. Set up environment variables:

   Create a `.env` file in the root directory and add the following variables:

    ```bash
    PORT=3000
    DATABASE_URL=your_database_connection_string
    JWT_SECRET=your_jwt_secret_key
    STRIPE_SECRET_KEY=your_stripe_secret_key
    MUX_TOKEN_ID=your_mux_token_id
    MUX_TOKEN_SECRET=your_mux_token_secret
    ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3000` to view the application.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any new features, improvements, or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## License

For any inquiries or issues, please contact us at [easykelchimdikejohn@gmail.com](mailto:easykelchimdikejohn@gmail.com).
