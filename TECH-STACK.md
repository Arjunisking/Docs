Document 3: Tech Stack Document
What is a Tech Stack Document?
A Tech Stack Document specifies which technologies, frameworks, libraries, and tools will be
used to build your website. It ensures the AI uses the right technologies for your project's
requirements.
Why You Need a Tech Stack Document:
• Ensures compatibility between different components
• Optimizes performance for your specific needs
• Makes the project maintainable and scalable
• Prevents the AI from using outdated or inappropriate technologies
• Provides clear technical foundation for development
What to Include in Your Tech Stack Document
1. Frontend Framework
• React, Vue, Angular, or vanilla JavaScript
• Specific version if important
• Why this framework for your project
2. Meta-Framework (if applicable)
• Next.js, Nuxt, Gatsby, etc.
• Rendering strategy (SSR, SSG, CSR)
3. Styling Solution
• CSS framework (Tailwind, Bootstrap, Material-UI)
• CSS-in-JS libraries
• Preprocessors (Sass, Less)
4. Backend (if needed)
• Node.js, Python, PHP, etc.
• Framework (Express, FastAPI, Laravel)
• Database (PostgreSQL, MongoDB, Firebase)
5. Key Libraries & Packages
• Form handling (React Hook Form, Formik)
• State management (Redux, Zustand, Context API)
• Animation libraries (Framer Motion, GSAP)
• Icon libraries (React Icons, Font Awesome)
6. Deployment & Hosting
• Hosting platform (Vercel, Netlify, AWS)
• Domain setup
• CI/CD requirements
7. Additional Tools
• Analytics (Google Analytics, Plausible)
• SEO tools
• Performance monitoring
Example: Tech Stack for Cafe Website
Project Type: Cafe Website with Reservation System
Frontend Framework:
• Next.js 14 (React-based meta-framework)
• Reason: Built-in SSR for SEO, image optimization, fast page loads
Styling:
• Tailwind CSS
• Reason: Fast development, easy customization, responsive utilities
UI Components:
• shadcn/ui components
• React Icons for iconography
Form Handling:
• React Hook Form for reservation forms
• Zod for validation
Backend:
• Next.js API Routes for simple endpoints
• MongoDB for storing reservations
• Nodemailer for email notifications
Additional Libraries:
• Framer Motion for smooth animations
• React DatePicker for reservation calendar
• Google Maps API for location map
Deployment:
• Vercel (automatic deployment from GitHub)
• Custom domain with SSL
Analytics & SEO:
• Google Analytics 4
• Next.js built-in SEO optimization
• Open Graph meta tags for social sharing
Performance:
• Next.js Image component for optimized images
• Lazy loading for below-the-fold content
• Code splitting for faster initial load
AI Prompts to Create Your Tech Stack Document
Prompt 1: Complete Tech Stack Recommendation
"I'm building a [PROJECT TYPE] website with these requirements:
• [List key features - e.g., user authentication, payment processing, real-time updates]
• [Performance requirements - e.g., must load in under 2 seconds]
• [Scale - e.g., expect 10,000 visitors/month]
• [Special requirements - e.g., must work offline, needs mobile app later]
Create a comprehensive Tech Stack Document that includes:
1. Recommended frontend framework and why
2. Styling solution best suited for the project
3. Backend technology (if needed)
4. Database choice with justification
5. Essential libraries and packages
6. Deployment and hosting recommendations
7. Development tools and workflow
Explain why each technology is recommended for this specific use case."
Prompt 2: Modern Best Practices
"Update this tech stack to follow 2024-2025 best practices for [PROJECT TYPE]:
[Paste your current tech choices]
Consider:
• Latest stable versions
• Performance optimization
• Developer experience
• Maintenance and scalability
• Cost-effectiveness
Provide alternatives if current choices are outdated or suboptimal."
Prompt 3: Feature-Specific Technology
"I need to implement [SPECIFIC FEATURE - e.g., real-time chat, payment
processing, image upload] in my website. What technologies, libraries, and APIs
should I use?
My current tech stack:
• Frontend: [Your framework]
• Backend: [Your backend]
• Database: [Your database]
Recommend the best tools that integrate well with my existing stack.
