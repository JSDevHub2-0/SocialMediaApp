
# **Social Media App** 🌐✨  
A full-stack social media app packed with modern features for an engaging user experience.  

## **🚀 Features**  
### **Core Features**  
- **Infinite Scrolling Feeds**: Seamless content exploration.  
- **Optimistic Updates**: Instant feedback for user actions.  
- **Like, Follow & Comment Systems**: Classic social features reimagined.  
- **Direct Messaging (DM)**: Chat powered by **Stream**.  
- **Hashtags & Mentions**: Enhance discoverability.  
- **File Uploads**: Drag & drop or copy-paste files with **UploadThing**.  
- **Notifications**: Stay updated with real-time alerts.  
- **Post Bookmarks**: Save your favorite content for later.  

### **Additional Features**  
- Full-text Search  
- Advanced Caching & Revalidation  
- Real-time Form Validation with **React Hook Form & Zod**  
- **Themes**: Dark, Light, or System themes.  
- Mobile-Responsive Design  

---

## **🛠️ Technologies & Tools**  
### **Frontend**  
- **Next.js 15**: Leveraging server actions & server components.  
- **TanStack React Query**: For state management and server-side data fetching.  
- **TipTap Editor**: A powerful, extensible text editor.  

### **Backend**  
- **Prisma ORM**: Efficient data modeling and querying.  
- **Postgres Database**: A reliable, scalable database solution.  

### **Authentication**  
- **Lucia Authentication**: Secure login with **username/password** & **Google OAuth2**.  

### **Styling**  
- **Tailwind CSS** & **Shadcn UI**: Beautiful and responsive layouts.  

### **Deployment**  
- Hosted on **Vercel** with cron jobs for scheduled tasks.  

<p>
<img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" height="25px"/>
<img alt="Prisma" src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" height="25px"/>
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" height="25px"/>
<img alt="Lucia Auth" src="https://img.shields.io/badge/Lucia_Auth-2088FF?style=for-the-badge&logo=lock&logoColor=white" height="25px"/>
<img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" height="25px"/>
<img alt="Shadcn UI" src="https://img.shields.io/badge/Shadcn_UI-000000?style=for-the-badge&logo=ui-components&logoColor=white" height="25px"/>
<img alt="TanStack Query" src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=tanstack&logoColor=white" height="25px"/>
<img alt="Stream Chat" src="https://img.shields.io/badge/Stream_Chat-005FFF?style=for-the-badge&logo=stream&logoColor=white" height="25px"/>
<img alt="UploadThing" src="https://img.shields.io/badge/UploadThing-FF5722?style=for-the-badge&logo=upload&logoColor=white" height="25px"/>
<img alt="React Hook Form" src="https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge&logo=react-hook-form&logoColor=white" height="25px"/>
<img alt="Vercel" src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" height="25px"/>
<img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" height="25px"/>
<img alt="Zod" src="https://img.shields.io/badge/Zod-FF7F50?style=for-the-badge&logo=z&logoColor=white" height="25px"/>
</p>

---

## **📸 Screenshots**  
*(Add screenshots showcasing your app's features and layout.)*  

---

## **🖥️ Installation & Setup**  

### **1. Clone the Repository**  
```bash  
git clone https://github.com/JSDevHub2-0/SocialMediaApp  
cd SocialMediaApp  
```  

### **2. Install Dependencies**  
```bash  
npm i --legacy-peer-deps
```  

### **3. Environment Variables**  
Create a `.env` file in the root directory and configure the following:  
```env  
DATABASE_URL=your_postgres_database_url  
NEXT_PUBLIC_GOOGLE_CLIENT_ID=your_google_client_id  
NEXT_PUBLIC_GOOGLE_CLIENT_SECRET=your_google_client_secret  
```  

### **4. Prisma Migration**  
```bash  
npx prisma migrate dev  
```  

### **5. Run the Development Server**  
```bash  
npm run dev  
```  
Open [http://localhost:3000](http://localhost:3000) in your browser.  

---

## **🚀 Deployment**  
Deploy your app seamlessly with **Vercel**:  
```bash  
npm run build  
vercel deploy  
```  

---

## **🤝 Contributions**  
Contributions are welcome!  
1. Fork the repository.  
2. Create your feature branch (`git checkout -b feature-name`).  
3. Commit your changes (`git commit -m "Add feature name"`).  
4. Push to the branch (`git push origin feature-name`).  
5. Open a Pull Request.  

---

## **📜 License**  
This project is licensed under the MIT License.  

---

## **🌟 Acknowledgments**  
- [Next.js](https://nextjs.org/)  
- [Prisma](https://www.prisma.io/)  
- [Lucia Auth](https://lucia-auth.vercel.app/)  
- [TanStack Query](https://tanstack.com/query/latest)  
- [Tailwind CSS](https://tailwindcss.com/)  
- [Shadcn UI](https://shadcn.dev/)  
- [UploadThing](https://uploadthing.com/)  
- [Stream Chat](https://getstream.io/chat/)  


