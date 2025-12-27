# FIRESTORE KNOWLEDGE BASE GENERATOR

## OBJECTIVE
Create 8 production-ready HTML files (1 index + 7 modules) for Firestore documentation with modern dark theme and interactive features.

---

## INPUT SOURCES

### Visual References (Provided Files)
Analyze uploaded MongoDB HTML files to extract and replicate:
- Theme styling (gradients, colors, typography)
- Layout patterns (cards, grids, headers, responsive design)
- Interactive features (search, filters, tag chips, "Open All" button)
- Code block syntax highlighting (CSS classes)
- Component styles (info/warning/tip boxes, tables, badges)

### Content Sources (Auto-Research)
Extract from official documentation:
- firebase.google.com/docs/firestore
- cloud.google.com/firestore
- Other sources...

Research topics per module:
1. **Foundations**: NoSQL concepts, documents/collections, subcollections, data types
2. **CRUD**: SDK initialization, .add/.set/.get/.update/.delete, batch operations
3. **Querying**: .where() operators, compound queries, .orderBy(), pagination, cursors
4. **Indexing**: Single-field vs composite indexes, optimization, limits (200 max)
5. **Realtime**: .onSnapshot() listeners, lifecycle management, offline behavior
6. **Security**: Rules syntax, auth patterns, request/resource objects, common recipes
7. **Advanced**: Transactions, batched writes, Cloud Functions, cost optimization

Code examples needed: JavaScript, Dart, Swift, Kotlin, Python

---

## OUTPUT SPECIFICATIONS

### File Structure
index.html # Master navigation with search/filter
1.Firestore-Foundations-DataModel.html # Green gradient (#11998e to #38ef7d)
2.Firestore-CRUD-Operations.html # Purple gradient (#667eea to #764ba2)
3.Firestore-Querying-Filtering.html # Cyan gradient (#06beb6 to #48b1bf)
4.Firestore-Indexing-Performance.html # Orange gradient (#f2994a to #f2c94c)
5.Firestore-Realtime-Listeners.html # Red gradient (#ee0979 to #ff6a00)
6.Firestore-Security-Rules.html # Pink gradient (#feac5e to #c779d0)
7.Firestore-Advanced-Patterns.html # Dark gradient (#0f0c29 to #302b63)

text

### Module Content Pattern
Each module HTML includes:
- Hero header (gradient background, module title, badge)
- 2-column responsive grid (concepts + code examples)
- Multi-language code tabs (JS, Dart, Swift, Kotlin, Python)
- Comparison tables (Firestore vs alternatives, best practices vs anti-patterns)
- Highlight boxes (💡 info blue, ⚠️ warning red, ✅ tip green)
- Learning checklist at end

### Index.html Features
- 7 module cards with descriptions and tags
- Live search bar with filter chips
- "Open Filtered" button for batch opening
- Learning timeline (Weeks 1-15)
- 3 practice projects:
  * Chat App (Modules 1-2)
  * E-commerce Catalog (Modules 3-5)
  * Social Feed (Modules 6-7)
- Resources section

---

## TECHNICAL REQUIREMENTS

### Styling
- Vanilla CSS inline in `<style>` tag
- Dark theme base: #0f172a background, #e2e8f0 text
- Syntax highlighting classes: .code-keyword, .code-string, .code-method, .code-number, .code-prop, .code-comment
- Responsive: mobile <768px, tablet 768-1120px, desktop >1120px

### Functionality
- Vanilla JavaScript inline in `<script>` tag
- Search filters by: module name, tags, description
- Tag chips toggle filtering (single-select)
- Live counter: "X / 7 modules shown"
- Clear button resets filters

### Format
- Self-contained files (no external dependencies)
- Relative links with URL encoding (spaces → %20)
- File size <5MB each
- Title format: "Firestore Cheat Sheet #X - Module Name"

---

## EXECUTION WORKFLOW

1. **Parse References**: Analyze MongoDB HTML structure and styling patterns
2. **Research Content**: Extract Firestore documentation for 7 modules
3. **Generate Files**: Create 8 complete HTML files matching reference style with Firestore content
4. **Validate**: Ensure all code examples accurate, links functional, styling consistent
5. **Output**: Place all files in Assets tab for download

Use my Notion connector to store and track your plan

---

## DELIVERABLES

8 complete HTML files ready for immediate deployment. Each file must be functional, visually consistent with MongoDB references, and contain accurate Firestore documentation.

BEGIN EXECUTION.