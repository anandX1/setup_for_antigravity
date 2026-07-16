# 🛠️ Antigravity Skills - Complete Reference

**Created by:** Anand Kumar  
**Contact:** anandkumar.3042008@gmail.com | Discord: ._.anand._. | Instagram: @anandx.1

---

## What are Skills?

Skills are **reusable, task-specific workflows** for common development tasks.

**Use by typing:** `/skill-name your request`

**Key difference from Agents:**
- Agents = Specialized personas (long-lived expertise)
- Skills = Focused tasks (get one job done well)

---

## 🎯 Available Skills

### 1. **api-scaffold** 🔌

**Purpose:** Generate production-ready REST/GraphQL API endpoints

**When to use:**
- Creating new API endpoints
- Need validation, auth, error handling
- Want database integration
- Need OpenAPI documentation

**Example:**
```
/api-scaffold Create a CRUD API for users with JWT authentication
```

**Output includes:**
- ✅ Route handlers
- ✅ Input validation (zod/pydantic)
- ✅ Auth middleware
- ✅ Database integration
- ✅ Error handling
- ✅ Unit tests
- ✅ OpenAPI docs

---

### 2. **ui-component** 🎨

**Purpose:** Build accessible, responsive React components

**When to use:**
- Creating React components
- Building pages/layouts
- Need responsive design
- Want accessibility

**Example:**
```
/ui-component Build a user profile card with avatar, name, and bio
```

**Output includes:**
- ✅ TypeScript component
- ✅ Tailwind styling
- ✅ Mobile-responsive
- ✅ ARIA labels
- ✅ Storybook docs
- ✅ Unit tests
- ✅ Prop interfaces

---

### 3. **ml-pipeline** 📊

**Purpose:** Create data pipelines and ML workflows

**When to use:**
- Building ETL workflows
- Creating ML pipelines
- Feature engineering
- Data validation

**Example:**
```
/ml-pipeline Build an Airflow pipeline:
- Fetch from S3
- Transform data
- Train model
- Log results to MLflow
```

**Output includes:**
- ✅ Airflow DAG code
- ✅ Data validation
- ✅ Feature engineering
- ✅ Model training
- ✅ Error handling
- ✅ Monitoring

---

### 4. **devops-setup** ☁️

**Purpose:** Setup infrastructure, Docker, and CI/CD

**When to use:**
- Creating Dockerfiles
- Setting up GitHub Actions
- Creating Terraform configs
- Deploying apps

**Example:**
```
/devops-setup Setup Docker and GitHub Actions:
- Build Node.js app
- Run tests
- Deploy to AWS ECS
- Setup monitoring
```

**Output includes:**
- ✅ Multi-stage Dockerfile
- ✅ Docker Compose
- ✅ GitHub Actions
- ✅ Terraform config
- ✅ Environment setup
- ✅ Monitoring

---

### 5. **database-migration** 💾

**Purpose:** Create and manage database schema changes

**When to use:**
- Adding tables
- Modifying schema
- Creating relationships
- Running migrations

**Example:**
```
/database-migration Add a posts table with user relationship and timestamps
```

**Output includes:**
- ✅ Migration file
- ✅ Schema definition
- ✅ Indexes
- ✅ Constraints
- ✅ Rollback script
- ✅ Validation

---

### 6. **code-review** 🔍

**Purpose:** Review code for security, performance, quality

**When to use:**
- Before merging PRs
- Security audit
- Performance concerns
- Code quality check

**Example:**
```
/code-review Review this auth module for security issues
```

**Output includes:**
- ✅ Security check
- ✅ Performance analysis
- ✅ Quality suggestions
- ✅ Best practices
- ✅ Test coverage
- ✅ Recommendations

---

## 📖 How to Use Skills

### In VS Code Copilot Chat

```
/api-scaffold Create a CRUD endpoint for products with pagination
```

### In GitHub Issues

```
@copilot /ui-component build a login form with email and password validation
```

### In Comments

```
@copilot /code-review Check for SQL injection vulnerabilities in this code
```

---

## 🎯 Skill Selection Guide

| Task | Skill | Command |
|------|-------|----------|
| Build API endpoint | api-scaffold | `/api-scaffold Create CRUD for users` |
| Create React component | ui-component | `/ui-component Build a button component` |
| Build data pipeline | ml-pipeline | `/ml-pipeline Create ETL workflow` |
| Setup Docker/CI-CD | devops-setup | `/devops-setup Setup GitHub Actions` |
| Add database table | database-migration | `/database-migration Add products table` |
| Review code | code-review | `/code-review Audit security` |

---

## 🚀 Advanced Usage

### Combine Multiple Skills

```
@copilot /database-migration add users table
then /api-scaffold create auth endpoints
then /ui-component build login form
```

Copilot will:
1. Create database schema
2. Generate API endpoints
3. Build UI component
4. Connect them together

### Use with Agents

```
@copilot use backend agent then /api-scaffold for authentication system
```

Gets:
- Backend agent's expertise
- Specific implementation from skill

### Complete Feature Chain

```
@copilot use full-stack agent:
1. /database-migration add posts table
2. /api-scaffold create posts API
3. /ui-component build posts list
4. /code-review security check
5. /devops-setup setup CI/CD
```

---

## 💡 Best Practices

1. **Be Specific**
   - ❌ "/api-scaffold Build API"
   - ✅ "/api-scaffold Create CRUD for products with JWT auth"

2. **Provide Context**
   - What framework?
   - What database?
   - Existing patterns?
   - Performance needs?

3. **Review Output**
   - Always check generated code
   - Test before merging
   - Learn from patterns

4. **Iterate**
   - Ask for improvements
   - Adjust as needed
   - Refine output

5. **Combine Tools**
   - Agents + Skills = powerful
   - Multiple skills in one request
   - Chain for complete features

---

## 📁 Skill Structure

Each skill in `.github/skills/` has:

```
skill-name/
├── SKILL.md              # Main instructions
├── references/           # Documentation
│   └── patterns.md
├── templates/            # Starter code
│   └── scaffold.ts
└── scripts/              # Helpers
    └── helper.py
```

---

## 🔗 Related Resources

- **[Agents Guide](./docs/AGENTS_GUIDE.md)** - Using agents
- **[Getting Started](./docs/GETTING_STARTED.md)** - Setup
- **[Architecture](./docs/ARCHITECTURE.md)** - System design
- **[Languages](./docs/LANGUAGES.md)** - When to use what
- **[Troubleshooting](./docs/TROUBLESHOOTING.md)** - Common issues

---

## 🆘 Need Help?

- 📧 Email: anandkumar.3042008@gmail.com
- 💬 Discord: ._.anand._.
- 📸 Instagram: @anandx.1
- 🐛 [GitHub Issues](https://github.com/anandX1/setup_for_antigravity/issues)
- 💡 [GitHub Discussions](https://github.com/anandX1/setup_for_antigravity/discussions)

---

**Questions?** Check [TROUBLESHOOTING.md](./docs/TROUBLESHOOTING.md) or reach out!
