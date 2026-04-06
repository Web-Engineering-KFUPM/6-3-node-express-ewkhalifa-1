# 6-3-node-express-main — Feedback

## Submission

- **Lab:** 6-3-node-express-main
- **Deadline (Riyadh / UTC+03:00):** 2026-04-06T20:59:00+03:00
- **Last commit time (from git log):** 2026-04-06T07:32:17+00:00
- **Submission marks:** **20/20** (On time)


## Files Checked

- Repo root (cwd): /Users/eyad./swe363/activity/6.3/6-3-node-express-ewkhalifa-1/6-3-node-express
- Detected project root: /Users/eyad./swe363/activity/6.3/6-3-node-express-ewkhalifa-1/6-3-node-express
- Backend folder: ✅ /Users/eyad./swe363/activity/6.3/6-3-node-express-ewkhalifa-1/6-3-node-express/backend
- Utils folder: ✅ /Users/eyad./swe363/activity/6.3/6-3-node-express-ewkhalifa-1/6-3-node-express/backend/utils
- Server: ✅ /Users/eyad./swe363/activity/6.3/6-3-node-express-ewkhalifa-1/6-3-node-express/backend/server.js
- Quotes: ✅ /Users/eyad./swe363/activity/6.3/6-3-node-express-ewkhalifa-1/6-3-node-express/backend/quotes.js
- Random: ✅ /Users/eyad./swe363/activity/6.3/6-3-node-express-ewkhalifa-1/6-3-node-express/backend/utils/random.js

---

## TODO-by-TODO Feedback

### TODO 1: Initialize Express app in backend/server.js — **10/10**

**Checklist**
- ✅ Imports express using import express from "express"
- ✅ Creates the Express app using const app = express()
- ✅ Defines PORT

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 2: Implement getRandomInt(max) in backend/utils/random.js — **10/10**

**Checklist**
- ✅ Exports getRandomInt(max)
- ✅ Uses Math.random()
- ✅ Uses Math.floor(...)
- ✅ Uses max in the random integer calculation and returns a value

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 3: Implement getRandomQuote() in backend/quotes.js — **10/10**

**Checklist**
- ✅ Imports getRandomInt from ./utils/random.js
- ✅ Exports getRandomQuote()
- ✅ Uses getRandomInt(quotes.length) or equivalent
- ✅ Returns one quote from the quotes array

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 4: Enable CORS middleware in backend/server.js — **10/10**

**Checklist**
- ✅ Imports cors using import cors from "cors"
- ✅ Applies CORS middleware using app.use(cors())

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 5: Add Morgan logger middleware in backend/server.js — **10/10**

**Checklist**
- ✅ Imports morgan using import morgan from "morgan"
- ✅ Applies Morgan middleware using app.use(morgan("dev"))

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 6: Define root and quote API routes in backend/server.js — **20/20**

**Checklist**
- ✅ Imports getRandomQuote from ./quotes.js
- ✅ Defines root route app.get("/")
- ✅ Root route sends plain text using res.send(...)
- ✅ Defines quote API route app.get("/api/quote")
- ✅ Quote API route calls getRandomQuote()
- ✅ Quote API route returns JSON using res.json({ quote }) or equivalent

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 7: Start the server with app.listen(...) in backend/server.js — **10/10**

**Checklist**
- ✅ Starts the server using app.listen(...)
- ✅ Uses PORT in app.listen(PORT, ...)
- ✅ Logs a server-start message using console.log(...)

**Deductions / Notes**
- ✅ No deductions. Good job!

---

## How marks were deducted (rules)

- JS comments are ignored (so starter TODO comments do NOT count).
- Checks are intentionally lenient, but include top-level implementation logic.
- Code can be in ANY order; repeated code is allowed.
- Common equivalents are accepted, and naming is flexible where possible.
- npm install commands and manual testing commands are NOT graded.
- Missing required items reduce marks proportionally within that TODO.
- Morgan only gets marks if it is both imported and applied as middleware.
- Route checks only verify top-level implementation, not exact response text wording.
