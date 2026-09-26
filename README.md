# Hi, I'm Dinesh

CS undergrad at Bangalore Institute of Technology (class of 2028) by day, freelance
full-stack developer by night, and occasionally by 3am. I build web apps end to end,
from the schema to the deploy button, and some of them have paying clients.

### What I actually do

- **Full-stack apps that survive real users**: React and Next.js on top of Node, with MongoDB or SQL underneath.
- **Marketplaces and booking systems**, which is mostly the art of stopping two people from booking the same 4pm slot.
- **The unglamorous production bits**: image pipelines, emails that actually arrive, cron jobs, auth, and making bots feel unwelcome.
- **Motion and WebGL**, with `prefers-reduced-motion` respected, because not everyone wants the page to do a backflip.

### Featured work

**[Wed Me Royal](https://www.wedmeroyal.com)**: big fat Indian weddings, fewer phone calls. A live client
marketplace where vendors list services with Cloudinary galleries and couples browse, book and review. Bookings
nobody confirms expire on their own through a node-cron job that emails everyone about it, so no vendor is
left holding a date for a couple who ghosted. Also: an admin dashboard, CSRF protection, rate limiting and reCAPTCHA.
*React · Express · MongoDB · Cloudinary · Brevo · Render.* Client code, so the repo is private.

**[Halvard](https://github.com/Dinesh282828/halvard)**: an architecture studio that doesn't exist, with a website
that very much does. GSAP-pinned scroll sequences, Lenis smooth scrolling and hand-written WebGL image distortion,
all in about 139 kB of gzipped JavaScript. No three.js, because a few hundred kilobytes is a lot to spend on
drawing one rectangle.
*React · TypeScript · Vite · GSAP · WebGL.*

**Orrery** *(in progress)*: 480 students, 430 different course baskets, one timetable. Under NEP every student
picks their own courses, so the old "class batch" is gone and so is every tool built on it. Orrery schedules
individual enrolments with a zero-dependency simulated-annealing solver, and when no timetable is possible it
doesn't just shrug: it tells you which lecturer is four periods short, and tests the fix before suggesting it.
*Next.js · React · JavaScript · SQLite.*

**Booked** *(in progress)*: booking software with one sacred rule: never let two people book the same slot. It
re-checks availability at the very last moment, because race conditions don't make appointments. Branded
booking pages and an owner dashboard come with it.
*Next.js · TypeScript · Prisma · Tailwind CSS.*

Orrery and Booked live in private repos; code is available on request.

### The stack, as a config file

```ts
const dinesh = {
  basedIn: "Bengaluru",
  frontend: ["React", "Next.js", "TypeScript", "Vite", "Tailwind CSS", "GSAP", "WebGL"],
  backend: ["Node.js", "Express", "Next.js server actions", "REST", "Server-Sent Events"],
  data: ["MongoDB (Mongoose)", "SQLite", "Prisma"],
  services: ["Cloudinary", "Brevo SMTP", "node-cron"],
  shipsTo: ["Render", "Vercel"],
  currentlyGrinding: "LeetCode, one LRU cache at a time",
};
```

### Say hi

Open to freelance projects, internships and full-time roles. If you need something built, or a timetable
everyone swears is impossible, [email me](mailto:dineshbalwan103@gmail.com).
