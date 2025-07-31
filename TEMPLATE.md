# Policy Documentation Template

Use this template when adding a new country to an existing policy page or creating a new policy category.

## For Adding a Country to Existing Policy

```markdown
## 🇦🇺 Australia
- 🔗 [Policy Name](https://official-government-link.gov.au)
- 📄 Excerpt:
  > "Official policy text excerpt that demonstrates the policy requirement or recommendation..."

### Additional Details (Optional)
- **Effective Date**: YYYY-MM-DD
- **Issuing Authority**: Department/Ministry Name
- **Scope**: Federal/State/Local level
- **Implementation**: Brief note on how the policy is implemented
```

## For Creating New Policy Category

### 1. Page Header Template

```markdown
# Policy Category Name

_Description_: Brief one-sentence description explaining what this policy type covers and its purpose.

---

## 🧩 How to contribute

To add a country to this policy, copy and paste this block below:

```markdown
## 🇨🇴 Colombia
- 🔗 [Official link](https://example.gov)
- 📄 Excerpt:
  > Policy text that demonstrates this type of policy...
```

---

[Country entries follow here using the template above]
```

### 2. Required Elements

Every policy page must include:

- **Clear title** describing the policy type
- **Description** explaining the policy's purpose and scope
- **Contribution template** for easy additions
- **At least 2-3 country examples** to establish the pattern

### 3. Country Entry Requirements

Each country entry must have:

- **Flag emoji** using ISO country code format (🇦🇺, 🇧🇷, 🇨🇦, etc.)
- **Official link** to government source
- **Policy excerpt** demonstrating the policy requirement
- **Accurate translation** if policy is not in English

## Formatting Guidelines

### Links
- Always use descriptive link text, not raw URLs
- Link directly to official government sources when possible
- If linking to archived or translated versions, note this clearly

### Excerpts
- Use blockquotes (>) for all policy text
- Include enough context to understand the policy requirement
- Maintain original language when possible
- If translating, note the original language

### Countries
- List countries alphabetically by country name (not flag emoji)
- Use official country names in English
- Include relevant subdivisions when policies are regional (e.g., "Germany - Federal", "United States - California")

## Translation Template

When creating translations, maintain the same structure:

### Spanish Version
```markdown
# [Nombre de la Política]

_Descripción_: [Descripción de una oración sobre la política]

---

## 🧩 Cómo contribuir

Para agregar un país a esta política, copia y pega este bloque a continuación:

```markdown
## 🇨🇴 Colombia
- 🔗 [Enlace oficial](https://example.gov)
- 📄 Extracto:
  > Texto de la política que demuestra este tipo de política...
```
```

### Portuguese Version
```markdown
# [Nome da Política]

_Descrição_: [Descrição de uma frase sobre a política]

---

## 🧩 Como contribuir

Para adicionar um país a esta política, copie e cole este bloco abaixo:

```markdown
## 🇨🇴 Colômbia
- 🔗 [Link oficial](https://example.gov)
- 📄 Trecho:
  > Texto da política que demonstra este tipo de política...
```
```

## Quality Checklist

Before submitting, verify:

- [ ] All links work and point to official sources
- [ ] Policy excerpts are accurate and properly attributed
- [ ] Formatting follows the established pattern
- [ ] Country flag emojis use correct ISO codes
- [ ] Translations are accurate and maintain formal tone
- [ ] Information is current and verifiable

## Examples of Good vs. Poor Entries

### ✅ Good Example
```markdown
## 🇫🇷 France
- 🔗 [Circular on the use of free software in public administration](https://www.legifrance.gouv.fr/circulaire/id/44411)
- 📄 Excerpt:
  > "Public administrations are encouraged to contribute to open source projects and to release under free licenses the source code of software they develop."
```

### ❌ Poor Example
```markdown
## France
- Link: https://legifrance.gouv.fr/circulaire/id/44411
- They require open source
```

The good example includes:
- Proper flag emoji
- Descriptive link text
- Official policy excerpt
- Clear formatting

The poor example lacks:
- Flag emoji
- Descriptive link text
- Proper excerpt formatting
- Sufficient detail
