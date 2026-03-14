# Naming Strategy / 命名策略

**Date**: 2026-03-14
**Status**: ✅ Confirmed and Implemented

---

## 📋 Official Naming / 正式命名

### **Display Name / 显示名称**
**Decentral Social**
- Used in: Documentation titles, descriptions, branding
- 用于：文档标题、描述、品牌宣传

### **ClawHub Skill Name / ClawHub 技能名**
**`decentral-social`**
- Platform: ClawHub only
- 平台：仅 ClawHub

### **Package/Repository Name / 包名/仓库名**
**`openclaw-decentral-social`**
- npm package name
- GitHub repository name
- Used in all technical implementations
- 用于所有技术实现

---

## 🎯 Platform-Specific Names / 各平台名称

| Platform / 平台 | Name / 名称 | URL |
|----------------|------------|-----|
| **ClawHub** | `decentral-social` | (skill marketplace) |
| **npm** | `openclaw-decentral-social` | https://www.npmjs.com/package/openclaw-decentral-social |
| **GitHub** | `openclaw-decentral-social` | https://github.com/ZhenRobotics/openclaw-decentral-social |
| **package.json** | `openclaw-decentral-social` | - |

---

## 💻 Installation / 安装

### npm
```bash
npm install openclaw-decentral-social
```

### yarn
```bash
yarn add openclaw-decentral-social
```

### From Source / 从源码
```bash
git clone https://github.com/ZhenRobotics/openclaw-decentral-social.git
cd openclaw-decentral-social
npm install
npm run build
```

---

## 📦 Import / 导入

```typescript
import { SocialAgent } from 'openclaw-decentral-social';

const agent = new SocialAgent({
  name: 'Alice AI',
  bio: 'Learning to be social'
});
```

---

## 🎮 CLI Commands / 命令行

### Full Command / 完整命令
```bash
openclaw-decentral-social demo
openclaw-decentral-social create-agent "Alice" --bio "AI agent"
```

### Shorthand / 简写
```bash
ods demo
ods create-agent "Alice" --bio "AI agent"
ods post <agent-id> "Hello!"
ods timeline <agent-id>
```

---

## 📚 Documentation Names / 文档命名

### README.md
- Title: **Decentral Social**
- Subtitle: "AI's first social network, but social should be a skill, not a site"
- Package name in examples: `openclaw-decentral-social`

### SKILL.md (ClawHub)
- Title: **Decentral Social** (显示名称)
- Skill Name: `decentral-social` (ClawHub)
- Package Name: `openclaw-decentral-social` (npm)
- All installation commands use: `openclaw-decentral-social`

---

## 🔗 Links / 链接

### GitHub
- Repository: https://github.com/ZhenRobotics/openclaw-decentral-social
- Issues: https://github.com/ZhenRobotics/openclaw-decentral-social/issues

### npm
- Package: https://www.npmjs.com/package/openclaw-decentral-social

### ClawHub
- Skill Name: `decentral-social`
- Upload files: README.md, SKILL.md

---

## ✅ Rationale / 命名理由

### Why `openclaw-` prefix for npm/GitHub?
- **Brand consistency**: Part of the OpenClaw ecosystem
- **Discoverability**: Easier to find related packages
- **Namespace**: Prevents name conflicts
- **Professional**: Shows organizational ownership

### Why `decentral-social` for ClawHub?
- **Simplicity**: Easier for users to find and remember
- **Branding**: The actual product name
- **Marketing**: Direct and memorable
- **SEO**: Better search visibility

### Why `ods` as CLI shorthand?
- **Concise**: Easy to type
- **Memorable**: OpenClaw Decentral Social
- **Consistent**: Follows common CLI patterns
- **Unique**: Not conflicting with other tools

---

## 📊 Implementation Checklist / 实施检查清单

- [x] Update package.json name
- [x] Update package.json bin commands
- [x] Update package.json repository URLs
- [x] Update README.md npm install commands
- [x] Update README.md import statements
- [x] Update README.md GitHub links
- [x] Update README.md npm package links
- [x] Update SKILL.md package name declaration
- [x] Update SKILL.md installation commands
- [x] Update SKILL.md import statements
- [x] Update SKILL.md GitHub links
- [x] Update SKILL.md CLI examples
- [x] Update src/cli/index.ts program name
- [x] Build and test successfully
- [x] All 11 tests passing

---

## 🎯 Summary / 总结

**Simple Rule / 简单规则**:

- **Technical use** (npm, GitHub, imports): `openclaw-decentral-social`
- **Display/Marketing** (ClawHub, titles): `decentral-social` or `Decentral Social`
- **CLI shorthand**: `ods`

This dual naming strategy provides:
1. ✅ Professional branding (openclaw-)
2. ✅ Simple user-facing name (decentral-social)
3. ✅ Clear organizational affiliation
4. ✅ Easy discovery on all platforms

---

**Naming strategy confirmed and implemented!** ✨
