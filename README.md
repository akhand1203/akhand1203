```markdown
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0D1B2A&height=180&section=header&text=Akhand%20Pratap%20Singh&fontSize=32&fontColor=E0E1DD&animation=fadeIn&fontAlignY=35" width="100%" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&pause=1000&color=E0E1DD&center=true&vCenter=true&width=500&lines=Software+Development+Engineer;Full+Stack+Developer;React+%7C+Node.js+%7C+Java;Building+scalable+web+applications)](https://git.io/typing-svg)

</div>

---

## 👤 About Me

**B.Tech CSE (AI/ML)** student at **Ajay Kumar Garg Engineering College, Ghaziabad** (AKTU, 2023–2027). I build production-grade full-stack web applications with a strong focus on real-time systems, clean architecture, and developer experience. Currently sharpening my DSA & CP skills in **Java** while shipping real-world projects with **React** and **Node.js**.

---

## 🛠️ Tech Stack

<div align="center">

### Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white)
![Mapbox GL](https://img.shields.io/badge/Mapbox_GL-000000?style=flat-square&logo=mapbox&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socket.io&logoColor=white)
![Passport.js](https://img.shields.io/badge/Passport.js-34E27A?style=flat-square&logo=passport&logoColor=white)

### Database
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=flat-square&logo=mongoose&logoColor=white)

### Auth & Security
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Google OAuth](https://img.shields.io/badge/Google_OAuth_2.0-4285F4?style=flat-square&logo=google&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)

### AI & Cloud
![OpenAI](https://img.shields.io/badge/OpenAI_GPT-4o--mini-412991?style=flat-square&logo=openai&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazonaws&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-0066FF?style=flat-square&logo=razorpay&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-00E59B?style=flat-square&logo=render&logoColor=black)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)

</div>

---

## 🚀 Featured Projects

### 🚗 [Rath – Real-Time Ride Sharing Application](https://github.com/akhand1203)

> _A production-deployed, full-stack ride-sharing platform with real-time tracking, dual-role auth, and live map rendering._

| Aspect | Details |
|--------|---------|
| **Stack** | React.js 19 · Node.js · Express.js · MongoDB · Socket.IO · Mapbox GL · JWT · Clerk · GSAP |
| **Deploy** | Vercel (Frontend) · Render (Backend) · MongoDB Atlas |

**Key Highlights:**
- 🔐 Engineered completely isolated **JWT + Clerk** authentication flows for **riders** and **captains**, eliminating cross-role token misuse
- 🛣️ Designed **16+ RESTful API endpoints** across 4 route modules (`user`, `captain`, `ride`, `map`) with role-scoped Express middleware and consistent error schemas
- ⚡ Reduced captain dispatch latency by **~40%** by replacing polling with **event-driven Socket.IO** tracking and **Haversine geospatial matching**
- 🗺️ Achieved **sub-2s map render times** with optimised Mapbox GL marker update cycles for live routes, pins, and captain positions
- 🐛 Eliminated a critical **race-condition bug** in ride acceptance using a `useRef` guard + idempotent server-side checks
- 🌐 Resolved production issues including **CORS**, **JWT expiry**, and **socket transport failures** across split architecture

<br>

### 🤖 [JobHunt – AI-Powered Job Portal](https://github.com/akhand1203)

> _A scalable full-stack job portal with AI-driven ATS resume scoring, role-based dashboards, and payment integration._

| Aspect | Details |
|--------|---------|
| **Stack** | React.js · Node.js · Express.js · MongoDB · Redux Toolkit · OpenAI GPT-4o-mini · AWS S3 · Razorpay · Google OAuth 2.0 |
| **Features** | 11 backend route modules · ATS Scoring · Role-based Dashboards · Payment Gating |

**Key Highlights:**
- 🏗️ Architected **11 backend route modules** handling the complete **recruiter–applicant lifecycle** — job posting, applications, ATS scoring, and premium plans
- 🧠 Integrated **OpenAI GPT-4o-mini** to build an ATS resume scorer that parses PDFs server-side, returning structured scores, keyword gaps, and improvement suggestions
- 📁 Implemented secure file handling with **AWS S3 presigned URLs**, eliminating server-side proxying and reducing upload/download latency
- 🔄 Managed auth state with **Redux Toolkit** — persisting sessions across routes and protecting role-specific pages via custom `ProtectedRoute` components
- 🔒 Secured the platform with **JWT**, **Google OAuth 2.0** (Passport.js), and **role-based access control**; integrated **Razorpay** with server-side signature verification for premium gating

---

## 🎓 Education

| Institution | Program | Duration |
|-------------|---------|----------|
| **Ajay Kumar Garg Engineering College, Ghaziabad** | B.Tech – Computer Science & Engineering (AI/ML) · AKTU | 2023 – 2027 |

---

## 📫 Connect With Me

<div align="center">

<a href="mailto:akhand1203@gmail.com">
  <img src="https://img.shields.io/badge/Email-akhand1203@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://linkedin.com/in/akhand1203">
  <img src="https://img.shields.io/badge/LinkedIn-akhand1203-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="https://github.com/akhand1203">
  <img src="https://img.shields.io/badge/GitHub-akhand1203-181717?style=flat-square&logo=github&logoColor=white" />
</a>
&nbsp;
<a href="tel:+919554425583">
  <img src="https://img.shields.io/badge/Phone-+91%2095544%2025583-25D366?style=flat-square&logo=whatsapp&logoColor=white" />
</a>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0D1B2A&height=100&section=footer" width="100%" />

</div>
```
