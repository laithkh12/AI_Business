
# AiLocalBusinessApp

## Overview

AiLocalBusinessApp is a local business directory web application built using **React**, **Next.js**, **TypeScript**, **MongoDB**, and **Google Generative AI**. It allows users to add, manage, and search for businesses. The application also features user authentication via **Clerk**, dynamic theming, business listings with pagination, and AI-generated business descriptions.

## Features

- **Light/Dark Theme**: Toggle between light and dark themes.
- **User Authentication**: Integration with **Clerk** for user sign-in and sign-out.
- **Business Listings**: Add and manage local businesses, including business details like name, category, address, phone, email, etc.
- **AI Generated Descriptions**: Use Google Generative AI to create SEO-optimized descriptions for businesses.
- **Admin Features**: Admin can manage all businesses, while owners can only edit their own business.
- **Live Preview**: See a live preview of business information while adding or editing.
- **Logo Upload**: Upload business logos to **Cloudinary**.
- **Search and Filtering**: Search for businesses and filter by category and location.
- **Pagination**: Paginate business listings for better user experience.
- **Responsive Design**: Fully responsive for desktop and mobile devices.

## Tech Stack

- **Frontend**: React, Next.js, TypeScript
- **Authentication**: Clerk
- **Database**: MongoDB
- **AI**: Google Generative AI for business description generation
- **File Storage**: Cloudinary for business logos
- **UI Components**: ShadCN-UI and Lucide React icons
- **Editor**: React Quill for rich text editing

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AiLocalBusinessApp.git
   ```

2. Navigate into the project folder:
   ```bash
   cd AiLocalBusinessApp
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up environment variables:
   Create a `.env.local` file in the root directory and add the following variables:
   ```plaintext
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your-publishable-key
   CLERK_SECRET_KEY=your-secret-key
   DATABASE=your-mongo-db-connection-string
   CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
   CLOUDINARY_API_KEY=your-cloudinary-api-key
   CLOUDINARY_API_SECRET=your-cloudinary-api-secret
   GEMINI_API_KEY=your-gemini-api-key
   ```

5. Run the application locally:
   ```bash
   npm run dev
   ```

   The app will be available at [http://localhost:3000](http://localhost:3000).

## Features in Detail

- **Business Management**: Add, edit, and delete businesses. Each business has a unique identifier and owner.
- **Admin Dashboard**: Admins can view and manage all businesses, while users can only manage their own.
- **Dynamic AI Description**: Businesses can have AI-generated descriptions, which are created by Google Generative AI.
- **File Upload**: Users can upload logos for their businesses, which are then stored in Cloudinary.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to fork and contribute to the project. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## Contact

If you have any questions or suggestions, feel free to reach out at [your-email@example.com](mailto:your-email@example.com).

## Acknowledgements

- [Clerk](https://clerk.dev/) for authentication services.
- [Google Generative AI](https://cloud.google.com/generative-ai) for AI-powered business descriptions.
- [Cloudinary](https://cloudinary.com/) for file storage.
- [ShadCN-UI](https://github.com/shadcn-ui) for UI components.
- [Lucide](https://lucide.dev/) for icons.

---

Thank you for checking out AiLocalBusinessApp!
