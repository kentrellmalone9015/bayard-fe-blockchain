## **Technologies Used**

- Next.js
- React
- TypeScript
- Tailwind CSS
- Radix UI components
- Framer Motion for animations
- React Spring for animations
- React Hot Toast for notifications
- Axios for API requests

## **Getting Started**

1. Clone the repository
2. Install dependencies: `npm install`
3. Set up environment variables: 
   - `BAYARD_API_KEY`: API key for the Bayard API
4. Run the development server: `npm run dev`
5. Open <http://localhost:3000> in your browser

## **About Bayard**

**Bayard_One** is an innovative open-source retrieval-augmented generative AI assistant that aims to transform the way researchers, academics, and community members engage with  scholarship.\
\
By integrating a vast collection of **over 20,000 research papers**, journals, and resources, Bayard_One provides a centralized platform for exploring the diverse and complex landscape of knowledge, fostering a deeper understanding of the community's experiences, challenges, and triumphs.

## **Features**

- Chat interface for querying the AI assistant
- Retrieval of relevant research documents
- Document summaries and abstracts
- Resizable panels for chat and document display
- Smooth animations and transitions
- Loading indicators and status updates
- Copy, share, and provide feedback on chat messages
- Regenerate responses
- Keyboard shortcuts for sending messages


## **Folder Structure**

- `app/`: Next.js app directory 
  - `page.tsx`: Main chat page component
- `components/`: Reusable UI components
- `pages/api/`: API routes 
  - `bayard-proxy.ts`: Proxy route for Bayard API requests
- `public/`: Public assets
- `styles/`: Global styles

## **Contributing**

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Make your changes and commit them: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Submit a pull request

