<h1 align="center">Anindya Mitra</h1>

<p align="center">
  <strong>Full-stack engineer and founder at <a href="https://folkwaretech.coop">Folkware Technologies</a>, a worker-owned software cooperative in Kolkata</strong>
</p>

<p align="center">
  Most of what I build is used by unions, worker organisations, and small teams<br />
  who have no ops department to catch it when it breaks.
</p>

<p align="center">
  <a href="https://folkwaretech.coop">Work</a> ·
  <a href="mailto:anindya@folkwaretech.coop">Email</a> ·
  <a href="https://www.linkedin.com/in/anindya24mitra/">LinkedIn</a>
</p>

<p align="center">
  <img src="./assets/focus.svg" width="820" alt="Current focus: tools for unions, co-ops, and small teams; owned end to end, from schema to deploy; built to keep running without me." />
</p>

## The short version

I usually own a product end to end: schema, API, interface, deploy, and whatever breaks afterwards. The teams I work with are small, often four or five people carrying an entire product line, and at that size a clever architecture nobody has time to operate is worse than a boring one that runs itself.

In practice that means:

- Two products needing the same capability get a versioned package they both install, not a third service to babysit
- Auth and permissions designed once and properly, with a break-glass path for whoever is on support that week
- Loading, empty, and error states built as part of the feature, not queued as polish for a sprint that never comes
- Handover notes good enough that the project survives me leaving it

## Selected work

| Product | What I built, and the hard part |
| --- | --- |
| **[Dotra](https://folkwaretech.coop/projects/dotra)** | Padel analytics that run from a courtside camera to a phone. I'm the primary engineer on both the Expo app and the NestJS backend: the recording and upload pipeline, queue and Step Function orchestration through PBVision's computer-vision engine, live match state over websockets, and iOS Live Activities for scores. Venues have unreliable networks, so the pipeline has to assume footage arrives late and out of order.<br><sub>Expo / React Native · NestJS · MongoDB · Redis + BullMQ · AWS</sub> |
| **[ZusGPT](https://folkwaretech.coop/projects/zusgpt)** | Four AI writing tools sold as one subscription. I built the NestJS backend and most of the Next.js front end: OpenAI and Gemini behind one interface, a credit ledger that meters every generation, Stripe subscriptions, and the referral and affiliate programmes on top. Metering is the interesting part, because a failed generation that still bills a customer is worse than one that fails loudly.<br><sub>Next.js · NestJS · MongoDB · Stripe · OpenAI + Gemini</sub> |
| **The Jarrow ecosystem**<br><sub>[Jarrow Insights](https://folkwaretech.coop/projects/jarrow-insights), [Worker Academy](https://folkwaretech.coop/projects/worker-academy), and internal platforms</sub> | Campaign asset management, worker education, publishing, and private knowledge tools for trade unions and organising groups. My longest-running work, and the one that is really about architecture: action-level permissions resolved from groups and per-user overrides on top of Keycloak, an S3 asset library with print-order and artwork workflows, and shared packages, a broadcast-email plugin and a file and workspace core, that the apps install instead of reimplementing.<br><sub>Next.js · NestJS · Payload CMS · Keycloak · Typesense · MongoDB</sub> |

The same thread runs through the smaller work: [Rise Movement](https://folkwaretech.coop/projects/rise-movement), [Unionise.ai](https://folkwaretech.coop/projects/unionise-ai), and [Skate.coop](https://folkwaretech.coop/projects/skate-coop) are all unions, cooperatives, or political movements. Nearly all of it is private client code, so the case studies cover outcomes rather than implementation.

## How I work

**Ask the awkward questions in week one.** Who owns this data, who pays for the storage, what happens when the person who requested the feature leaves. These only get more expensive the longer you postpone them.

**Boring where it counts.** A well-drawn module boundary beats a distributed system that needs a full-time operator. The infrastructure is rarely the interesting part of the product.

**Stay after launch.** I maintain most of what I ship, which changes how I build it. You stop leaving problems for whoever comes next once you work out that it's going to be you.

## What's public here

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=demosthenix&amp;background=0D1117&amp;border=30363D&amp;stroke=30363D&amp;ring=E85D04&amp;fire=E85D04&amp;currStreakNum=F0F6FC&amp;sideNums=F0F6FC&amp;currStreakLabel=8B949E&amp;sideLabels=8B949E&amp;dates=8B949E&amp;border_radius=12" />
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=demosthenix&amp;background=F6F8FA&amp;border=D0D7DE&amp;stroke=D0D7DE&amp;ring=E85D04&amp;fire=E85D04&amp;currStreakNum=24292F&amp;sideNums=24292F&amp;currStreakLabel=57606A&amp;sideLabels=57606A&amp;dates=57606A&amp;border_radius=12" />
    <img src="https://streak-stats.demolab.com?user=demosthenix&amp;ring=E85D04&amp;fire=E85D04&amp;border_radius=12" height="190" alt="Anindya's total contributions, current streak, and longest streak" />
  </picture>
</p>

<p align="center"><sub>Client work lives in private repositories, so this is a partial picture. The public repos are mostly older side projects and things I built to learn something.</sub></p>

## What I reach for

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" height="42" alt="TypeScript" title="TypeScript" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" height="42" alt="React and React Native" title="React / React Native" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nextjs/nextjs-original.svg" height="42" alt="Next.js" title="Next.js" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg" height="42" alt="Node.js" title="Node.js" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nestjs/nestjs-original.svg" height="42" alt="NestJS" title="NestJS" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" height="42" alt="Tailwind CSS" title="Tailwind CSS" />
  &nbsp;&nbsp;
  <img src="https://payloadcms.com/images/favicon.svg" height="42" alt="Payload CMS" title="Payload CMS" />
</p>

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg" height="42" alt="MongoDB" title="MongoDB" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/redis/redis-original.svg" height="42" alt="Redis" title="Redis" />
  &nbsp;&nbsp;
  <img src="https://typesense.org/favicon.png" height="42" alt="Typesense" title="Typesense" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" height="42" alt="AWS" title="AWS" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/googlecloud/googlecloud-original.svg" height="42" alt="Google Cloud" title="Google Cloud" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" height="42" alt="Docker" title="Docker" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cloudflare/cloudflare-original.svg" height="42" alt="Cloudflare" title="Cloudflare" />
</p>

<p align="center"><sub>TypeScript wherever it will go, and whatever the problem actually calls for after that.</sub></p>

## Get in touch

I take on client work through [Folkware Technologies](https://folkwaretech.coop), where a handful of us build software for organisations that can't afford to be anyone's growth experiment.

If something in your product or platform is stuck, tell me what it is: **[anindya@folkwaretech.coop](mailto:anindya@folkwaretech.coop)**
