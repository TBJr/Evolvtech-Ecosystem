# Evolvtech Ecosystem

**About Evolvtech**  
Evolvtech is a technology company that builds sophisticated computer software and web-based business tools targeting multinational organizations. Our mission is to deliver a modular, enterprise-grade SaaS ecosystem—covering authentication, multitenancy, invoicing, CRM, analytics, and more—with world-class performance, security, and extensibility.

---

## 🚀 Quickstart

1. Clone the repo
   ```bash
   gh repo clone Evolvtech-Limited/ecosystem
   cd ecosystem
   
2. Install dependencies
    ```bash
    npm install
    
3. Start all services
    ```bash
    npm run dev:all

4. Open http://localhost:3000 in your browser

## 📁 Repository Structure

```bash
/
├─ apps/
│  ├─ dashboard/      # Next.js frontend shell
│  ├─ auth-service/   # NestJS microservice
│  └─ …               # other modules
├─ packages/
│  ├─ ui/             # shared components
│  ├─ db/             # Prisma schema & migrations
│  └─ config/         # env typing & constants
├─ infra/             # Terraform configs
├─ .github/           # CI workflows & issue templates
├─ .eslintrc.js
├─ .prettierrc
├─ commitlint.config.js
├─ turbo.json
└─ README.md
