SYSTEM ROLE:
You are a senior Google Cloud architect and technical documentation specialist with expertise in Firebase Firestore, NoSQL databases, and modern web development.

═══════════════════════════════════════════════════════════════

OBJECTIVE:
Create a complete, production-ready Firestore Knowledge Base consisting of 8 interactive HTML files with modern dark theme styling and professional documentation standards.

═══════════════════════════════════════════════════════════════

INPUT ANALYSIS:

REFERENCE FILES PROVIDED (Visual Templates):
The uploaded MongoDB HTML files serve as VISUAL AND STRUCTURAL REFERENCES for output format:
- index.html → Template for master navigation page
- MongoDB cheat sheets → Templates for module-specific styling patterns

FROM THESE REFERENCES, REPLICATE:
✓ Dark theme gradient backgrounds (#0f172a to #0b1222)
✓ Card-based layout with hover effects
✓ Live search/filter functionality with tag chips
✓ "Open Filtered" multi-tab feature
✓ Syntax-highlighted code blocks with CSS classes
✓ Responsive grid layouts (mobile/tablet/desktop)
✓ Info/Warning/Tip boxes with colored left borders
✓ Comparison tables with alternating row colors
✓ Icon headers and badge elements
✓ Footer metadata display

CONTENT SOURCES (Auto-Research Required):
You must research and extract content from:
1. Official Firestore Documentation:
   - firebase.google.com/docs/firestore (primary source)
   - cloud.google.com/firestore (Google Cloud variant)

2. Key Topics to Research Per Module:
   - Module 1: Data model, documents, collections, subcollections, data types
   - Module 2: SDK initialization, CRUD operations (.add, .set, .get, .update, .delete)
   - Module 3: Query operators, compound queries, ordering, pagination, cursors
   - Module 4: Indexing types, composite indexes, query optimization, EXPLAIN
   - Module 5: Real-time listeners, snapshots, onSnapshot(), detach patterns
   - Module 6: Security rules syntax, auth patterns, request/resource objects
   - Module 7: Transactions, batched writes, offline persistence, Cloud Functions

3. Code Examples Required:
   - JavaScript (Web SDK v9 modular)
   - Dart (Flutter)
   - Swift (iOS)
   - Kotlin (Android)
   - Python (Admin SDK)
   
4. Best Practices Sources:
   - Official best practices guides
   - Security rules cookbook/recipes
   - Performance optimization patterns
   - Common anti-patterns to avoid

═══════════════════════════════════════════════════════════════

OUTPUT REQUIREMENTS:

FILE STRUCTURE (8 HTML files total):

1. index.html
   - Master navigation page
   - 7 module cards with descriptions, tags, file links
   - Live search bar: "Search by module name/tag/topic... (e.g: security, queries, #3)"
   - Filter chips: All, Foundations, CRUD, Queries, Performance, Realtime, Security, Advanced
   - "Open Filtered (tabs)" button for batch opening
   - Learning timeline section (Weeks 1-15 progression)
   - 3 Practice projects section
   - Resources & references section
   - Meta display: "X / 7 modules shown"
   - Footer: File location hint

2. 1.Firestore-Foundations-DataModel.html
   - Firestore overview (NoSQL vs RDBMS comparison table)
   - Document & Collection architecture (with visual diagrams described in text)
   - Hierarchical data structures (parent-child relationships)
   - Subcollections (nesting patterns, limits)
   - Data types reference (String, Number, Boolean, Map, Array, Timestamp, GeoPoint, Reference)
   - Use cases for Data Analysts vs Systems Engineers
   - Learning checklist

3. 2.Firestore-CRUD-Operations.html
   - SDK initialization (Web, iOS, Android, Flutter, Python examples)
   - CREATE: .add() vs .set() with code examples
   - READ: .get() vs .onSnapshot() differences
   - UPDATE: .update() vs .set({merge: true})
   - DELETE: .delete() operations
   - Batch writes (batched creates/updates/deletes)
   - Practical examples (user registration, profile updates)

4. 3.Firestore-Querying-Filtering.html
   - Simple queries (.where() operators)
   - Comparison operators (==, !=, <, <=, >, >=, in, not-in, array-contains)
   - Compound queries (multiple .where() clauses)
   - Ordering (.orderBy()) and limiting (.limit())
   - Pagination strategies (startAt, startAfter, endAt, endBefore)
   - Query cursors with document snapshots
   - Query limitations table (max 30 disjunctions, etc.)

5. 4.Firestore-Indexing-Performance.html
   - Single-field vs composite indexes
   - Automatic indexing behavior
   - Creating composite indexes (firebase.json, console)
   - Index optimization strategies
   - Query performance analysis
   - Index limits (200 composite indexes per database)
   - Best practices (index only what you query)
   - Slow query identification

6. 5.Firestore-Realtime-Listeners.html
   - Snapshot listeners setup (.onSnapshot())
   - Real-time vs one-time fetch comparison
   - Listener lifecycle management
   - Detaching listeners (unsubscribe patterns)
   - Performance best practices (>30s lifetime recommendation)
   - Error handling for listeners
   - Offline behavior with listeners

7. 6.Firestore-Security-Rules.html
   - Security rules structure and syntax
   - Authentication-based rules (request.auth)
   - Read/write permissions (allow read, write)
   - request object (request.auth, request.time, request.resource)
   - resource object (resource.data)
   - Functions in rules (custom validation logic)
   - Wildcard paths ({userId}, {docId})
   - Common patterns cookbook:
     * User-owned data
     * Role-based access
     * Field validation
     * Read-only fields
   - Testing rules (Firebase Emulator)

8. 7.Firestore-Advanced-Patterns.html
   - Transactions (.runTransaction())
   - Batched writes (.batch())
   - Offline persistence (enablePersistence)
   - Cloud Functions triggers (onCreate, onUpdate, onDelete, onWrite)
   - Data modeling best practices (denormalization, arrays vs subcollections)
   - Migration strategies (from RTDB, from other NoSQL)
   - Cost optimization tips
   - Scaling patterns (sharding, partitioning)

═══════════════════════════════════════════════════════════════

MODULE COLOR SCHEMES (Apply unique gradients):

Module 1 (Foundations): 
  - Gradient: #134e5e to #71b280
  - Header: #11998e to #38ef7d
  - Accent: #2ecc71

Module 2 (CRUD): 
  - Gradient: #667eea to #764ba2
  - Header: #667eea to #764ba2
  - Accent: #7c3aed

Module 3 (Querying): 
  - Gradient: #06beb6 to #48b1bf
  - Header: #06beb6 to #48b1bf
  - Accent: #0891b2

Module 4 (Performance): 
  - Gradient: #f2994a to #f2c94c
  - Header: #f2994a to #f2c94c
  - Accent: #f59e0b

Module 5 (Realtime): 
  - Gradient: #ee0979 to #ff6a00
  - Header: #ee0979 to #ff6a00
  - Accent: #ef4444

Module 6 (Security): 
  - Gradient: #feac5e to #c779d0 to #4bc0c8
  - Header: #feac5e to #c779d0
  - Accent: #ec4899

Module 7 (Advanced): 
  - Gradient: #0f0c29 to #302b63 to #24243e
  - Header: #0f0c29 to #302b63
  - Accent: #6366f1

═══════════════════════════════════════════════════════════════

CONTENT STRUCTURE PER MODULE:

LAYOUT PATTERN (Replicate from MongoDB references):

1. Hero Header Section:
   - Full-width gradient background (module-specific)
   - Module title (h1) with icon/emoji
   - Subtitle describing module purpose
   - Colored badge with module number

2. Content Grid (2-column responsive):
   - Left column: Concept cards
   - Right column: Code examples
   - Mobile: Stack vertically

3. Card Components:
   Each card includes:
   - Icon + Title header (colored underline matching module theme)
   - Description paragraph
   - Code blocks OR comparison tables
   - Tags/pills for key concepts

4. Special Elements:
   - Info boxes (💡): Blue left border (#3b82f6)
   - Warning boxes (⚠️): Red left border (#ef4444)
   - Tip boxes (✅): Green left border (#10b981)
   - Best Practice boxes (🎯): Purple left border (#8b5cf6)

5. Code Blocks:
   Multi-language tabs (when applicable):

6. Comparison Tables:
| Feature | Firestore | RDBMS |
|---------|-----------|-------|
| ... | ... | ... |

7. Learning Checklist (end of module):
- [ ] Checkbox item 1
- [ ] Checkbox item 2
- [ ] Checkbox item 3

═══════════════════════════════════════════════════════════════

TECHNICAL IMPLEMENTATION:

CSS FRAMEWORK:
- Vanilla CSS only (no external dependencies)
- Inline <style> tag in <head>
- Dark theme base colors:
* Background: #0f172a, #0b1222
* Text: #e2e8f0, #cbd5e1
* Cards: #1e293b with subtle border
* Code blocks: #1f2937 background
- Responsive breakpoints:
* Mobile: <768px (1 column)
* Tablet: 768px-1120px (2 columns)
* Desktop: >1120px (3 columns for index grid)
- Smooth transitions: transform, box-shadow (0.3s ease)

SYNTAX HIGHLIGHTING (CSS classes):
.code-keyword { color: #ff7b72; } /* SELECT, const, let, func, etc. */
.code-string { color: #a5d6ff; } /* String literals */
.code-method { color: #d2a8ff; } /* Function names */
.code-number { color: #79c0ff; } /* Numbers */
.code-prop { color: #7ee787; } /* Properties/fields */
.code-comment { color: #6a737d; } /* Comments */

JAVASCRIPT FUNCTIONALITY (Vanilla ES6+):
- Live search filtering (searches: module name, tags, description)
- Tag chip filtering (single-select with "All" option)
- "Clear" button resets search and filters
- "Open Filtered (tabs)" opens matching modules with 60ms delays
- Live result counter updates: "X / 7 modules shown"
- All code inline in <script> tag before </body>

FILE PATHS:
- Use relative paths only
- URL-encode spaces: %20
- Example: href="1.Firestore-Foundations-DataModel.html"

METADATA (Every HTML file):
<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8"> <meta name="viewport" content="width=device-width, initial-scale=1.0"> <title>Firestore Cheat Sheet #X - Module Name</title> </head> ```
═══════════════════════════════════════════════════════════════

CONTENT EXTRACTION RULES:

FROM OFFICIAL DOCUMENTATION:

Extract code examples (preserve exact syntax)

Extract API reference signatures

Extract tables (convert to HTML <table>)

Extract best practices (convert to tip boxes)

Extract warnings/caveats (convert to warning boxes)

Identify common patterns (create code templates)

CONTENT ORGANIZATION:

Start with high-level concept explanation

Follow with syntax/API reference

Provide multiple code examples (simple → complex)

Include comparison tables where relevant

Add practical use cases (Data Analyst vs Systems Engineer)

End with best practices and checklist

CODE EXAMPLES MUST:

Be runnable and complete (not fragments)

Include imports/initialization

Show realistic variable names

Include comments explaining key lines

Cover common use cases

Show error handling where applicable

═══════════════════════════════════════════════════════════════

PRACTICE PROJECTS (Include in index.html):

Project 1 (Modules 1-2): Real-time Chat Application

Collections: users, chatrooms, messages (subcollections)

CRUD operations for messages

User authentication integration

Skills: Data modeling, basic CRUD

Project 2 (Modules 3-5): E-commerce Product Catalog

Complex queries (price range, categories, search)

Real-time inventory updates with listeners

Composite indexes for multi-field search

Pagination for product listing

Skills: Querying, indexing, real-time updates

Project 3 (Modules 6-7): Social Media Feed System

Advanced security rules (user-owned content, privacy)

Infinite scroll pagination

Cloud Functions for notifications

Transaction-based like/comment counters

Skills: Security, advanced patterns, Cloud Functions

═══════════════════════════════════════════════════════════════

LEARNING TIMELINE (Include in index.html):

Weeks 1-2: Module 1 (Foundations)

Understand NoSQL concepts vs RDBMS

Master document and collection model

Learn data types and structure design

Weeks 3-4: Module 2 (CRUD)

Initialize Firestore SDK

Execute all CRUD operations

Practice with sample datasets

Weeks 5-6: Module 3 (Querying)

Master query operators

Build compound queries

Implement pagination

Weeks 7-8: Module 4 (Indexing)

Understand indexing strategies

Create composite indexes

Optimize query performance

Weeks 9-10: Module 5 (Realtime)

Setup snapshot listeners

Manage listener lifecycle

Handle offline scenarios

Weeks 11-13: Module 6 (Security)

Write security rules

Implement authentication patterns

Test with Firebase Emulator

Weeks 14-15: Module 7 (Advanced)

Build transactions and batches

Integrate Cloud Functions

Apply production best practices

═══════════════════════════════════════════════════════════════

ADVANCED RESOURCES (Include in index.html):

Official Documentation:

Firebase Firestore Docs: firebase.google.com/docs/firestore

Google Cloud Firestore: cloud.google.com/firestore

Tools & Emulators:

Firebase CLI & Emulator Suite

Firestore Rules Playground

Firebase Extensions

Advanced Topics:

Firestore vs Realtime Database comparison

Multi-region replication strategies

Security rules unit testing

Cost optimization techniques

Firestore + Cloud Run integration

Community Resources:

Fireship.io Firestore tutorials

Firebase official YouTube channel

Stack Overflow firestore tag

═══════════════════════════════════════════════════════════════

QUALITY ASSURANCE CHECKLIST:

CONTENT ACCURACY:
✓ All code examples use correct SDK syntax (v9 modular for Web)
✓ No markdown remnants in HTML output
✓ All tables preserve data accurately
✓ Links between files work correctly
✓ API references match official documentation

VISUAL CONSISTENCY:
✓ All 7 modules follow identical layout pattern
✓ Index page replicates MongoDB index functionality
✓ Each module has unique color scheme
✓ Typography consistent (font-family, sizes, weights)
✓ Spacing and padding uniform across all cards

FUNCTIONALITY:
✓ Search returns correct results for all query types
✓ Tag filters accurately show/hide modules
✓ "Open All" works without browser popup blocking
✓ Responsive layout adapts to mobile/tablet/desktop
✓ All interactive elements have hover states
✓ Code blocks have proper syntax highlighting

PERFORMANCE:
✓ All CSS inline (no external files)
✓ All JavaScript inline and non-blocking
✓ No external image dependencies (use emojis for icons)
✓ Each file size <5MB
✓ Fast load time on mobile networks

ACCESSIBILITY:
✓ Semantic HTML structure
✓ Sufficient color contrast (WCAG AA)
✓ Keyboard navigation support
✓ Alt text for visual elements

═══════════════════════════════════════════════════════════════

OUTPUT DELIVERABLES:

Generate 8 complete, self-contained HTML files ready for deployment:

index.html

1.Firestore-Foundations-DataModel.html

2.Firestore-CRUD-Operations.html

3.Firestore-Querying-Filtering.html

4.Firestore-Indexing-Performance.html

5.Firestore-Realtime-Listeners.html

6.Firestore-Security-Rules.html

7.Firestore-Advanced-Patterns.html

Each file must be:

Fully functional standalone HTML document

Include all CSS inline in <style> tag

Include all JavaScript inline in <script> tag

Use only relative links to other files

Immediately usable without any modifications

Production-ready for deployment

PLACE ALL FILES IN ASSETS TAB FOR DOWNLOAD.

═══════════════════════════════════════════════════════════════

EXECUTION INSTRUCTIONS:

STEP 1: Analyze the provided MongoDB HTML reference files to understand:

Visual design patterns and color schemes

HTML structure and CSS class naming

JavaScript functionality implementation

Responsive layout techniques

STEP 2: Research Firestore documentation and extract content for each module:

Visit firebase.google.com/docs/firestore

Extract code examples for all SDKs (JS, Dart, Swift, Kotlin, Python)

Gather best practices and common patterns

Collect security rules examples

STEP 3: Generate all 8 HTML files following the exact structure and styling patterns from MongoDB references but with Firestore-specific content

STEP 4: Validate that all files are complete, functional, and visually consistent

STEP 5: Output all files to Assets tab for download

═══════════════════════════════════════════════════════════════

BEGIN EXECUTION: Generate all 8 HTML files now.