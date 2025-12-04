# 🚀 Skills Collection for AI Agents

Transform Droids into a specialized expert with modular skills that supercharge development workflows.

## 🎯 Quick Start

```bash
# Install all skills at once (14 total skills)
cp -r skills/* ~/.factory/skills/

# Or pick what you need
cp -r skills/svelte-design ~/.factory/skills/

# Install specific new skills
cp -r skills/security-auth ~/.factory/skills/
cp -r skills/api-builder ~/.factory/skills/
cp -r skills/devops-deployer ~/.factory/skills/
cp -r skills/qa-tester ~/.factory/skills/
cp -r skills/database-manager ~/.factory/skills/
cp -r skills/observability-monitor ~/.factory/skills/
cp -r skills/mobile-devops ~/.factory/skills/
```

## 🔍 Find Your Perfect Skill

### **Building User Interfaces?**
- [`svelte-design`](./skills/svelte-design) - Create distinctive, production-grade Svelte/SvelteKit interfaces
- [`svelte-ui-animator`](./skills/svelte-ui-animator) - Add purposeful animations with Svelte transitions and actions
- [`svelte-ui-integration`](./skills/svelte-ui-integration) - Build SvelteKit workflows with form actions and load functions
- [`shadcn-management`](./skills/shadcn-management) - Manage Svelte component libraries (shadcn-svelte, Skeleton UI, Melt UI)
- [`sveltekit-data-optimizer`](./skills/sveltekit-data-optimizer) - Optimize SvelteKit performance with load functions and progressive enhancement

### **Building Mobile Apps?**
- [`flutter-enterprise`](./skills/flutter-enterprise) - Build enterprise Flutter apps with clean architecture and feature-based structure
- [`flutter-ui-ux`](./skills/flutter-ui-ux) - Create beautiful, responsive Flutter UI with animations and custom themes

### **Developing Backend Systems?**
- [`backend-dev`](./skills/backend-dev) - Complete API design to deployment workflow

### **Planning & Documentation?**
- [`product-management`](./skills/product-management) - Write PRDs, analyze features, plan roadmaps
- [`task-generator`](./skills/task-generator) - Generate structured task lists from requirements
- [`agents-md-generator`](./skills/agents-md-generator) - Create AI-optimized documentation structures

### **Building Secure Applications?**
- [`security-auth`](./skills/security-auth) - Implement authentication, authorization, and security best practices

### **Developing APIs?**
- [`api-builder`](./skills/api-builder) - Design, build, and document RESTful APIs and GraphQL endpoints

### **Deploying to Production?**
- [`devops-deployer`](./skills/devops-deployer) - Set up CI/CD pipelines, containerization, and cloud deployment

### **Quality Assurance?**
- [`qa-tester`](./skills/qa-tester) - Create comprehensive test suites, automate testing, and ensure code quality

### **Managing Data?**
- [`database-manager`](./skills/database-manager) - Design schemas, optimize queries, and manage database systems

### **Monitoring Production?**
- [`observability-monitor`](./skills/observability-monitor) - Implement logging, metrics, and monitoring for production systems

### **Mobile Deployment?**
- [`mobile-devops`](./skills/mobile-devops) - Build, test, and deploy mobile apps to app stores

### **Automation & Tools?**
- [`browser`](./skills/browser) - Chrome DevTools automation and scraping
- [`skill-creator`](./skills/skill-creator) - Build your own AI skills
- [`template-skill`](./skills/template-skill) - Starting point for new skills

## 🛠️ Skill Anatomy

Each skill is a complete package:

```
skill-name/
├── SKILL.md              # Core instructions & workflows
├── references/           # Detailed docs & patterns
├── scripts/              # Automation utilities
└── assets/               # Templates & resources
```

## 💡 Popular Skill Combinations

### **Full-Stack Development**
```bash
# Perfect for building complete applications
skills/backend-dev + skills/svelte-design + skills/svelte-ui-integration
```

### **Mobile App Development**
```bash
# Complete Flutter app from architecture to UI
skills/flutter-enterprise + skills/flutter-ui-ux
```

### **Product Launch**
```bash
# From idea to deployment
skills/product-management + skills/backend-dev + skills/svelte-design
```

### **Performance Optimization**
```bash
# Speed up existing applications
skills/sveltekit-data-optimizer + skills/svelte-ui-animator
```

### **Secure API Development**
```bash
# Build secure, tested APIs with monitoring
skills/api-builder + skills/security-auth + skills/qa-tester + skills/observability-monitor
```

### **Full-Stack Production Deployment**
```bash
# Complete application from development to production monitoring
skills/backend-dev + skills/security-auth + skills/devops-deployer + skills/observability-monitor
```

### **Mobile App Production Pipeline**
```bash
# From development to app store deployment
skills/flutter-enterprise + skills/mobile-devops + skills/qa-tester
```

### **Data-Driven Application**
```bash
# Applications with robust data management and monitoring
skills/database-manager + skills/api-builder + skills/observability-monitor
```

## 🎨 Skill Showcase

### Frontend Excellence
- **Design Systems**: Create cohesive, scalable Svelte/SvelteKit interfaces
- **Animation Libraries**: Svelte transitions, actions, and custom animation patterns
- **Performance**: SvelteKit server-side rendering and progressive enhancement optimization
- **Component Management**: Streamlined Svelte component library workflows (shadcn-svelte, Skeleton, Melt UI)

### Mobile Development
- **Enterprise Architecture**: Feature-based clean architecture for scalable Flutter apps
- **UI/UX Excellence**: Responsive, animated Flutter interfaces with custom themes
- **Cross-Platform**: Single codebase for iOS and Android with platform-specific optimizations
- **Performance**: 60fps animations and optimized rendering for smooth mobile experiences

### Backend Mastery
- **Multi-Expert System**: Architect + Security + DevOps + Database specialists
- **Security-First**: Built-in authentication and protection patterns
- **CI/CD Ready**: Automated testing and deployment pipelines
- **Scalable Architecture**: Enterprise-grade design patterns

### Planning Precision
- **Structured Requirements**: RICE/ICE framework integration
- **Task Automation**: Junior-developer-friendly breakdowns
- **Documentation**: AI-optimized hierarchical structures
- **Research Synthesis**: User insights to actionable plans

### Security & Authentication
- **Zero-Trust Architecture**: JWT, OAuth2, and modern authentication patterns
- **Security Best Practices**: Input validation, encryption, and vulnerability protection
- **Authorization Systems**: Role-based access control and permission management
- **Security Testing**: Automated security scans and penetration testing workflows

### API Development & Integration
- **RESTful Design**: Clean API architecture with proper HTTP methods and status codes
- **GraphQL Implementation**: Flexible query interfaces and schema design
- **API Documentation**: OpenAPI/Swagger specifications and interactive docs
- **Integration Patterns**: Webhooks, event-driven architecture, and third-party integrations

### DevOps & Deployment
- **CI/CD Pipelines**: Automated testing, building, and deployment workflows
- **Container Orchestration**: Docker, Kubernetes, and microservices deployment
- **Cloud Infrastructure**: AWS, Azure, and GCP deployment automation
- **Infrastructure as Code**: Terraform and CloudFormation templates

### Quality Assurance
- **Test Automation**: Unit, integration, and end-to-end testing frameworks
- **Performance Testing**: Load testing and performance benchmarking
- **Code Quality**: Static analysis, linting, and code review automation
- **Test-Driven Development**: TDD workflows and behavior-driven development

### Database Management
- **Schema Design**: Normalized and denormalized database architectures
- **Query Optimization**: Indexing strategies and performance tuning
- **Data Migration**: Version-controlled database migrations
- **NoSQL Integration**: Document, key-value, and graph database implementations

### Observability & Monitoring
- **Logging Systems**: Structured logging and log aggregation
- **Metrics Collection**: Application performance monitoring and business metrics
- **Distributed Tracing**: Request tracking across microservices
- **Alerting Systems**: Proactive monitoring and incident response

### Mobile DevOps
- **App Store Deployment**: Automated builds for iOS App Store and Google Play
- **Mobile CI/CD**: Fastlane and other mobile-specific deployment tools
- **Version Management**: Semantic versioning and release automation
- **Device Testing**: Automated testing across multiple devices and OS versions

## 🚀 Real-World Workflows

### Building a Flutter Enterprise App
```
User: "Create an enterprise inventory management app"

→ flutter-enterprise analyzes requirements and designs feature-based clean architecture
→ flutter-enterprise sets up modular structure with data, domain, and presentation layers
→ flutter-ui-ux creates responsive UI components with custom themes
→ flutter-ui-ux adds smooth animations and micro-interactions
→ Result: Production-ready Flutter app with maintainable architecture and beautiful UI
```

### Creating a SvelteKit Landing Page
```
User: "Build a modern landing page"

→ svelte-design analyzes brand and creates aesthetic direction for Svelte
→ svelte-ui-animator adds Svelte transitions and scroll-reveal animations
→ shadcn-management provides Svelte component library integration
→ sveltekit-data-optimizer ensures instant server-side rendering
→ Result: Production-ready, animated SvelteKit landing page in minutes
```

### Launching an API
```
User: "Create a user management API"

→ backend-dev coordinates expert systems
→ Designs secure authentication and database schema
→ Sets up testing and deployment automation
→ Result: Enterprise-grade API with full CI/CD
```

### Planning a Feature
```
User: "Plan a new search feature"

→ product-management structures PRD and user stories
→ task-generator breaks down into actionable tasks
→ agents-md-generator creates documentation structure
→ Result: Complete spec with implementation roadmap
```

### Building a Secure API
```
User: "Create a secure payment processing API"

→ api-builder designs RESTful endpoints with proper HTTP methods
→ security-auth implements JWT authentication and OAuth2 flows
→ database-manager creates secure schema with encrypted sensitive data
→ qa-tester builds comprehensive test suites including security tests
→ observability-monitor sets up logging and alerting for payment transactions
→ Result: Enterprise-grade, secure API with full monitoring and testing coverage
```

### Deploying a Full-Stack Application
```
User: "Deploy our SaaS application to production"

→ devops-deployer sets up CI/CD pipeline with automated testing
→ security-auth implements SSL/TLS and security headers
→ observability-monitor configures application monitoring and alerting
→ database-manager handles database migration and backup strategies
→ qa-tester runs automated integration tests in staging environment
→ Result: Production-ready deployment with monitoring, security, and automated testing
```

### Mobile App Release Pipeline
```
User: "Release our mobile app to iOS and Android stores"

→ mobile-devops configures automated builds for both platforms
→ qa-tester runs device-specific tests and performance benchmarks
→ security-auth implements certificate pinning and secure storage
→ observability-monitor sets up crash reporting and analytics
→ devops-deployer manages rollback strategies and A/B testing
→ Result: Automated mobile release pipeline with monitoring and security
```

### Database Migration Project
```
User: "Migrate our database to a new architecture"

→ database-manager designs new schema and migration strategy
→ api-builder updates API endpoints to work with new database structure
→ qa-tester creates data validation tests and performance benchmarks
→ observability-monitor sets up database performance monitoring
→ devops-deployer orchestrates zero-downtime migration process
→ Result: Seamless database migration with data integrity and performance optimization
```

## 🛠️ Installation Guide

### Factory AI Users
```bash
# Copy all skills
cp -r skills/* ~/.factory/skills/

# Copy specific skill
cp -r skills/skill-name ~/.factory/skills/
```

### Manual Setup
1. Clone this repository
2. Copy skill folders to your AI agent's directory
3. Check individual skill READMEs for dependencies

## 🤝 Contribute

Building new skills? Follow our framework:

1. **Structure**: Use the standard anatomy (SKILL.md, references/, scripts/, assets/)
2. **Concise**: Keep SKILL.md under 500 lines
3. **Practical**: Include real examples with actual file paths
4. **Tested**: Validate with real-world scenarios

## 📄 Licensing

Each skill may have individual licenses. Check skill directories for specifics.

## 📋 Maintainer

**Anaz S. Aji**
[GitHub Profile](https://github.com/ajianaz)

---

**Built for [Factory AI](https://factory.ai) and compatible AI coding assistants.**

*Transform your AI assistant from generalist to specialist with targeted skills.*
