👋 Hello, my name is Piotr Lisowski. I’m interested in Java and Spring and I'm looking for a job as a Junior Java Developer.

Here you can find my two recruitment task. First (spring-gender-checker) was my first ever Java app. I devliered it on time, but code quality was not great, so I was not hired. But app is working as it should! :)

Requirement was to create app, that can detect gender by given name. First endpoint ("/first-variant") should return gender based on first word. For example "Jan Maria Rokita" is male, because only Jan is checked.

In second endpoint ("/second-variant") majority rule is used. For example "Jan Maria Rokita" is "inconclusive" because Jan is male, Maria is male and female name, and Rokita is unrecognized. There are also two endpoints ("/male-tokens") and ("/female-tokens") to return all available names.

Second app (apzumi-api) is downloading posts from public API (https://jsonplaceholder.typicode.com/posts) every 24 hours. Data are saved to database (H2) and there are endpoints to redownload, search, update and delete posts from database.

There was also some more requirements. For example downloading posts every 24 hours should not overwrite edited or deleted posts in database. There are also some tests, readme with changelog, and commits with some useful comments (hope so).

<!---
pioterl/pioterl is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me: piotr.lisow
--->
