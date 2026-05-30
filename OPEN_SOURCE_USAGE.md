# Open Source License & Usage Guide

## Quick Summary

✅ **You can:**
- Use in commercial projects
- Modify the code
- Distribute copies
- Create derivative works
- Sublicense (with restrictions)

❌ **You must:**
- Include the original license
- Include copyright notice
- State significant changes
- Not remove attribution

---

## MIT License - What It Means

UI UX Pro Max is released under the **MIT License**, one of the most permissive open-source licenses.

### The Three Requirements

#### 1. Include License Text

When distributing UI UX Pro Max (or derivatives), include the full license text:

```
MIT License

Copyright (c) 2024 Next Level Builder

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...
[Full license text]
```

#### 2. Include Copyright Notice

Maintain the original copyright:

```
Copyright (c) 2024 Next Level Builder
```

You may add your own copyright in addition to the original.

#### 3. Document Changes

If you modify the code, clearly indicate what changed:

```javascript
/**
 * Original: UI UX Pro Max (MIT License)
 * Copyright (c) 2024 Next Level Builder
 * 
 * Modifications: Added custom theme support
 * By: Your Name (2024)
 * 
 * This modified version retains the MIT License.
 */
```

---

## Common Usage Scenarios

### Scenario 1: Using in Your SaaS Product

✅ **Legal?** YES

**Requirements:**
1. Include MIT License in your `LICENSE` file
2. Include copyright notice
3. Document any modifications
4. Link to original repository (recommended)

**Example:**
```markdown
# Your Product License

This product incorporates UI UX Pro Max, licensed under the MIT License:

Copyright (c) 2024 Next Level Builder
[Full MIT License text]
[Link to original: github.com/NextGenAILLC/ui-ux-pro-max-nextgenaillc]

Modifications: [List your changes]
```

### Scenario 2: Selling a Modified Version

✅ **Legal?** YES (with conditions)

**Requirements:**
1. Include MIT License (same as above)
2. You CAN charge for your product
3. You CANNOT use "UI UX Pro Max" trademark
4. You MUST disclose it's based on UI UX Pro Max

**Example Product Listing:**
```
Cool Design System Pro

Based on open-source UI UX Pro Max (licensed under MIT)
with custom enhancements and support.

Original: github.com/NextGenAILLC/ui-ux-pro-max-nextgenaillc
License: MIT
```

### Scenario 3: Creating a Design System Fork

✅ **Legal?** YES

**Requirements:**
1. Include MIT License
2. Include copyright notice
3. Document modifications
4. Choose a different name
5. Link to original (GitHub, documentation, or both)

**Example Repository:**
```
# My Company Design System

Based on UI UX Pro Max (MIT License)
Copyright (c) 2024 Next Level Builder

This is a customized version for [Your Company]
with industry-specific additions.

Original: https://github.com/NextGenAILLC/ui-ux-pro-max-nextgenaillc
License: MIT (see LICENSE file)
Modifications: [List]
```

### Scenario 4: Distributing in npm

✅ **Legal?** YES (with license in package)

**Requirements:**
1. Include LICENSE file in package
2. Include copyright notice in package.json or README
3. Document modifications

**Example package.json:**
```json
{
  "name": "@yourcompany/design-system",
  "version": "1.0.0",
  "description": "Design system based on UI UX Pro Max",
  "license": "MIT",
  "repository": "github.com/yourcompany/design-system",
  "readme": "Based on UI UX Pro Max (MIT License). See LICENSE file.",
  "dependencies": {
    "uipro-cli": "^1.3.0"
  }
}
```

### Scenario 5: Using in Closed-Source Enterprise Software

✅ **Legal?** YES

**Requirements:**
1. Include MIT License in your license documentation
2. Include copyright notice
3. Must include or bundle the license file
4. Internal use only (not redistributed)

**Example Compliance:**
```
# OPEN SOURCE ATTRIBUTIONS

This software includes components from:

UI UX Pro Max
- License: MIT License
- Copyright: (c) 2024 Next Level Builder
- Source: https://github.com/NextGenAILLC/ui-ux-pro-max-nextgenaillc
- Modifications: Integrated into our design system [list changes]
```

---

## What You CANNOT Do

### ❌ Use the "UI UX Pro Max" Brand

Without permission:
- Cannot claim to be "UI UX Pro Max"
- Cannot use the logo
- Cannot use in product name (without clear distinction)

**OK:** "MySystem (powered by UI UX Pro Max)"
**NOT OK:** "UI UX Pro Max Plus" or "UI UX Pro Max Enterprise"

### ❌ Sublicense Under Different Terms

Your derivative must maintain MIT license compatibility. You cannot:
- Change to GPL or other restrictive license
- Add proprietary restrictions
- Claim exclusive rights

**OK:** MIT, Apache 2.0, or other permissive
**NOT OK:** GPL, Proprietary, or Commercial-only

### ❌ Remove Attribution

You must keep:
- Original copyright notice
- Reference to original project
- Link to source (recommended)

### ❌ Trademark Misuse

Cannot:
- Register "UI UX Pro Max" as your trademark
- Use official logo without permission
- Suggest official endorsement

---

## How to Properly License Your Work

### Template: Include in Your LICENSE file

```markdown
# [Your Product] License

## Your Code
[Your Copyright] - [Your License]

## Open Source Components

This software includes components from the following open-source projects:

### UI UX Pro Max
- License: MIT License
- Copyright: (c) 2024 Next Level Builder
- Source: https://github.com/NextGenAILLC/ui-ux-pro-max-nextgenaillc
- Changes: [Describe what you changed]

---

### MIT License - Full Text

[Include full MIT License text here]
```

### Template: Include in Your README

```markdown
## License & Attribution

This project is licensed under [Your License].

**Attribution:**
This project is based on [UI UX Pro Max](https://github.com/NextGenAILLC/ui-ux-pro-max-nextgenaillc)
licensed under the MIT License (Copyright © 2024 Next Level Builder).

**Modifications:**
- [Change 1]
- [Change 2]
```

---

## Compliance Checklist

### For Any Use

- [ ] Read the MIT License (in LICENSE file)
- [ ] Understand you can use commercially
- [ ] Plan to include license in distribution
- [ ] Prepare to document changes

### For Derivative Works

- [ ] Maintain MIT License compatibility
- [ ] Include original copyright notice
- [ ] Document modifications clearly
- [ ] Link to original repository
- [ ] Use different name if creating product

### For Commercial Distribution

- [ ] Include full LICENSE file
- [ ] Disclose based on UI UX Pro Max
- [ ] List modifications
- [ ] Include attribution in documentation
- [ ] Update in each version

### For Trademark Compliance

- [ ] Don't claim to be official UI UX Pro Max
- [ ] Don't use official logo without permission
- [ ] Clearly distinguish your modifications
- [ ] Don't suggest official endorsement

---

## FAQ

**Q: Can I use this in commercial software?**
A: Yes! MIT License explicitly allows commercial use.

**Q: Can I sell a product based on this?**
A: Yes, but you must include the MIT License and copyright notice.

**Q: Can I change the license?**
A: No, derivative works must use MIT (or compatible) license.

**Q: Do I have to open-source my modifications?**
A: No, MIT doesn't require it. But you must acknowledge the original license.

**Q: Can I use it without attribution?**
A: No, the copyright notice must be included.

**Q: What if I remove all attribution?**
A: That violates the license. You must include the license and copyright notice.

**Q: Can I use for government work?**
A: Yes, MIT is government-friendly.

**Q: Is there warranty?**
A: No, MIT includes "as-is" clause with no warranty.

**Q: Who owns my modifications?**
A: You do! Your modifications are your intellectual property.

---

## Getting Permission for Other Uses

Need to do something not covered above?

Contact: legal@nextgenaillc.dev

We may grant permission for:
- Trademark usage
- Proprietary sublicensing
- Other non-standard arrangements

---

## Resources

- **Official MIT License:** https://opensource.org/licenses/MIT
- **SPDX License ID:** MIT
- **License Explanation:** https://choosealicense.com/licenses/mit/
- **Legal Guidance:** https://www.synopsys.com/blogs/software-security/mit-license/

---

## Version History

- **v1.0** - 2024: Initial open source guide

---

**Last Updated:** 2024
**Maintained by:** NextGenAILLC Legal Team
