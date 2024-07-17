### 🛠 Changes being made

Here give examples of the changes you've made in this pull request. Include an itemized list if you can. It'll help the reviewer


### ✨ What's the context?

What's the context for the changes? Are there any


### 🧠 Rationale behind the change

Why did you choose to make these changes? Were there any trade-offs you had to consider? 


### 🧪 Test plan

How do you know the changes are safe to ship to production?


### 📸 Screenshots (optional)

If you made UI changes, what are the before an afters?


### 🏎 Quality check

- [ ] Are your changes following SOLID principles?
- [ ] Did you verify this functionality doesn't exist anywhere else in the code?
- [ ] Have you got your changes verified with JUnits?
- [ ] Have you got your changes performance evaluated?
- [ ] Are there any erroneous console logs, debuggers or leftover code in your changes?

### Writing to DB ? 
- [ ] Have you got the execution plan of the query verified?
- [ ] Are your queries using the right indexes, collation?
- [ ] Any N+1 queries?
- [ ] Are you inserting date time, if so are you inserting in UTC?
- [ ] If you have used currency, have you verified the unit of currency is correct?
- [ ] Are you certain that you are not breaking the data write and read contract with your dependent module?

### Updating DDL? 
Are you making any non backward compatible changes resulting in break of contract with your module. Have you ran the pact tests locally?

### Creating or updating a new API ? 
- [ ] Are you changing the signature of any Public, Private, Internal API in non backward compatible way.
- [ ] Have you followed the API standards?

### Any UI Changes?
- [ ] Are there any UI changes you made that must be notified to customers?
- [ ] Have you written Feature test for them ? 
- [ ] Have you commented on the complex sections of the code?
- [ ] Have you used memoization, caching to ensure better reuse of computed results?
  
