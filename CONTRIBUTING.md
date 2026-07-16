# 🤝 Contributing to Antigravity

**Maintained by:** Anand Kumar  
**Email:** anandkumar.3042008@gmail.com  
**Discord:** ._.anand._.  
**Instagram:** @anandx.1

---

## Getting Started

1. **Fork the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/setup_for_antigravity.git
   cd setup_for_antigravity
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Follow our guidelines** (see below)

4. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Create a Pull Request**

---

## Code Style Guidelines

### Commit Messages

```
type(scope): description

feat(agents): add new security agent
fix(setup): resolve Python path issue
docs(readme): update quick start guide
refactor(skills): improve api-scaffold
test(component): add missing tests
chore(deps): update dependencies
```

**Types:**
- `feat` - New feature
- `fix` - Bug fix
- `docs` - Documentation
- `refactor` - Code refactor
- `test` - Tests
- `chore` - Maintenance
- `perf` - Performance

### Pull Request Process

1. Update README.md if needed
2. Ensure all tests pass
3. Request review from maintainers
4. Address feedback
5. Squash commits before merge

---

## Adding New Features

### Add a New Agent

1. Create `.github/agents/your-agent.agent.md`
2. Follow YAML frontmatter format
3. Add detailed instructions
4. Update `AGENTS.md`
5. Update documentation

**Template:**
```markdown
---
name: Your Agent Name
description: What this agent does
model: Claude Sonnet 4
tools: ['codebase', 'terminal', 'github']
---

# Your Agent Name

Detailed instructions...
```

### Add a New Skill

1. Create `.github/skills/your-skill/SKILL.md`
2. Add references, templates, scripts
3. Update `skills.md`
4. Include examples

**Structure:**
```
.github/skills/your-skill/
├── SKILL.md              # Main instructions
├── references/           # Documentation
│   └── patterns.md
├── templates/            # Starter code
│   └── scaffold.ts
└── scripts/              # Helper scripts
    └── helper.py
```

---

## Reporting Issues

### Bug Report

- Clear, descriptive title
- Steps to reproduce
- Expected vs actual behavior
- Environment details
- Relevant logs/screenshots

### Feature Request

- Clear description
- Use case/problem solved
- Proposed solution
- Alternatives considered

---

## Code Standards

- Follow `.github/copilot-instructions.md`
- Use meaningful names
- Add comments for complex logic
- Include tests
- Update documentation

---

## Testing

```bash
# Run validation
./scripts/validate-setup.sh

# Run tests
npm test
pytest
```

---

## Documentation

- Update README.md for major changes
- Add JSDoc/docstrings
- Include code examples
- Keep guides up-to-date

---

## License

By contributing, you agree your contributions will be licensed under MIT License.

---

## Contact

- 📧 **Email**: anandkumar.3042008@gmail.com
- 💬 **Discord**: ._.anand._.
- 📸 **Instagram**: @anandx.1
- 🐛 **Issues**: [Report here](https://github.com/anandX1/setup_for_antigravity/issues)
- 💡 **Discussions**: [Join here](https://github.com/anandX1/setup_for_antigravity/discussions)

---

**Thank you for contributing! 🙌**
