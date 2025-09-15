# Interviewly

**Interviewly** is a comprehensive AI-powered interview preparation and hiring platform that connects candidates with interviewers through real-time collaboration, interactive assessments, and intelligent job matching.  

---

## 📸 Banner  
![Interviewly Banner](./public/banner.png) <!-- Replace with actual banner path -->

---

## 🚀 Features  

### 👨‍🎓 For Candidates  
- **AI-Powered Interview Preparation**: Personalized study plans based on skills, target position, and timeline  
- **Interactive Quiz Platform**: Auto-generated quizzes tailored to learning needs  
- **Flashcards System**: Create & manage flashcards with AI-generated answers  
- **Resume Builder**: AI-assisted resume templates  
- **Job Board**: Browse and apply to jobs with application tracking  
- **Interview Scheduling**: Manage mock interviews with real interviewers  
- **Real-time Video Interviews**: With integrated code editor & collaboration tools  
- **Performance Analytics**: Track progress with detailed insights  
- **Application Tracking**: Real-time updates on job applications  

### 🧑‍💼 For Interviewers/Employers  
- **Candidate Dashboard**: Review and manage applications  
- **Job Posting Management**: Create and edit job postings  
- **Interview Scheduling**: Assign coding problems & schedule interviews  
- **Real-time Interview Tools**: Live code editor, notes, recording  
- **Application Review System**: Update statuses & give feedback  
- **Email Notifications**: Automated updates  
- **Activity Tracking**: Monitor platform activities  

### 🛠️ Core Features  
- Real-time collaboration (code editing, notes, video calls)  
- AI integration with **Google Gemini API**  
- Secure **role-based access control** (candidates & interviewers)  
- Modern UI with **Next.js 14, Tailwind, Framer Motion**  
- Real-time sync with **Convex database**  
- Email system with **React Email + Resend**  
- High-quality video conferencing via **Stream API**  

---

## 💻 Tech Stack  

### Frontend  
- **Framework**: Next.js 14 (App Router)  
- **Language**: TypeScript  
- **Styling**: Tailwind CSS  
- **Animations**: Framer Motion  
- **Icons**: Lucide React  

### Backend  
- **Database**: Convex (real-time)  
- **Auth**: Clerk + JWT  
- **API**: Serverless functions & webhooks  
- **Email**: React Email + Resend  
- **Video**: Stream API  

### DevOps  
- **Hosting**: Vercel  
- **Monitoring**: Vercel Analytics  
- **Version Control**: Git + GitHub  

---

## 🏗️ Architecture  

- **Server Components** with optimized data fetching  
- **Convex** for real-time synchronization  
- **Clerk Authentication** for secure multi-provider auth  
- **REST API Layer** with serverless functions  
- **Webhook-driven** event architecture  

---
```
## 📁 Project Structure
 interviewly/
├── convex/ # Convex schema & backend functions
├── emails/ # Email templates
├── src/
│ ├── app/ # Next.js App Router
│ ├── components/ # Reusable components
│ ├── hooks/ # Custom hooks
│ ├── lib/ # Utility functions
│ └── constants/ # Global constants
└── public/ # Static assets
```
---

---

## 🔒 Authentication & Authorization  
- Multi-provider login (Email, Social, SIWE)  
- JWT integration with Convex  
- Role-based UI (candidates vs. interviewers)  
- Database-level access control  

---

## 🔄 Real-time Features  
- Live interview sessions (video + collaborative coding)  
- Instant notifications & updates  
- Real-time job tracking  
- Synchronized data across devices  

---

## 🧠 AI Integration (Google Gemini API)  
- Personalized study plans  
- AI quiz & flashcard generation  
- Resume optimization  
- Automated feedback & insights  
- AI-driven job-candidate matching  

---

## 🎯 Candidate Journey  
1. Sign up & create profile  
2. Get AI-powered study plan  
3. Practice with quizzes, flashcards, coding problems  
4. Apply to jobs & track status  
5. Schedule & attend interviews  
6. Track analytics & performance  

### Interviewer Journey  
1. Create interviewer profile  
2. Post job openings  
3. Review candidates  
4. Schedule interviews with coding tasks  
5. Conduct live interviews  
6. Give feedback & update status  

---

## 🚀 Getting Started  

### Prerequisites  
- Node.js 18+  
- Clerk account (authentication)  
- Convex account (database)  
- Resend account (emails)  
- Stream API (video)  
- Google Gemini API key  

### Installation  

```bash
# Clone repo
git clone https://github.com/Pankajjaiswal07/interviewly.git
cd interviewly

# Install dependencies
npm install
# or
yarn install
---
```
```
📱 Responsive Design

Desktop: Full-featured experience

Tablet: Optimized for touch

Mobile: Streamlined UI

🔐 Security

End-to-end encryption for sensitive data

JWT-based authentication

Role-based access control

GDPR compliant

📧 Email Notifications

Interview confirmations

Job application updates

Application reminders

Employer notifications

🎨 UI/UX

Clean modern design with dark/light themes

Framer Motion animations

WCAG accessibility compliance

Loading skeletons & smooth UX

📝 License

This project is licensed under the MIT License.

👥 Contributing

Fork the repo

Create a feature branch (git checkout -b feature/awesome)

Commit changes (git commit -m 'Add awesome feature')

Push branch (git push origin feature/awesome)

Open a Pull Request

📧 Contact

For support or queries: pankaj172005@gmail.com
```

