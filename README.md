# Hi, I'm Dinesh Balwan

Computer Science undergraduate at Bangalore Institute of Technology (B.E., class of 2028)
and freelance full-stack developer based in Bengaluru. I build web applications
end to end, from the data model and API to the interface and deployment, and I
have shipped production work for paying clients.

### What I build

- **Full-stack web apps**: React and Next.js frontends on Node.js APIs backed by MongoDB or SQL
- **Marketplaces and booking systems**: listings, bookings, reviews and admin dashboards
- **The production side**: image pipelines, transactional email, scheduled jobs, auth, and hardening against CSRF, abuse and bots
- **Interfaces with motion**: scroll choreography and WebGL effects that stay fast and accessible

### Tech stack

- **Frontend**: React, Next.js, TypeScript, JavaScript, Vite, Tailwind CSS, GSAP, WebGL
- **Backend**: Node.js, Express, Next.js server actions, REST APIs, Server-Sent Events, JWT and session auth
- **Data**: MongoDB (Mongoose), SQLite, Prisma
- **Services**: Cloudinary, Brevo SMTP, node-cron
- **Deployment**: Render, Vercel, Git

### Featured work

**[Wed Me Royal](https://www.wedmeroyal.com)**: live client project, an Indian wedding vendor marketplace.
Vendors list services with Cloudinary-hosted galleries; couples browse, book and review. Pending bookings
expire automatically through a node-cron job that sends Brevo email notices, and the site includes
an admin dashboard, CSRF protection, rate limiting and reCAPTCHA.
*React · Express · MongoDB · Cloudinary · Brevo · Render.* Client code, so the repository is private.

**[Halvard](https://github.com/Dinesh282828/halvard)**: a motion-led website for a fictional architecture
studio, with GSAP-pinned scroll sequences, Lenis smooth scrolling and hand-written WebGL image distortion
in about 139 kB of gzipped JavaScript. It honours `prefers-reduced-motion` throughout.
*React · TypeScript · Vite · GSAP · WebGL.*

**Orrery** *(in progress)*: a timetabling engine for NEP/CBCS colleges, where every student picks their own
courses. It schedules from individual enrolments rather than fixed class batches (the demo college's
480 students have 430 distinct course baskets), using a zero-dependency solver built on simulated annealing.
When no timetable is possible, it explains which constraints collide and tests the smallest fix before
suggesting it. *Next.js · React · JavaScript · SQLite.*

**Booked** *(in progress)*: a booking SaaS for studios and independent professionals, with branded public
booking pages, an owner dashboard and a scheduling engine that re-checks availability at booking time
to prevent double bookings. *Next.js · TypeScript · Prisma · Tailwind CSS.*

Orrery and Booked are in private repositories; code is available on request.

### Contact

Open to freelance projects, internships and full-time roles.

- Email: [dineshbalwan103@gmail.com](mailto:dineshbalwan103@gmail.com)
- Location: Bengaluru, India
