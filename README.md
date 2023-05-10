- 👋 Hi, I’m @Pejabat122
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Pejabat122/Pejabat122 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
const xhr = new XMLHttpRequest();
xhr.open('GET', 'https://example.com/api/data');
xhr.onload = () => {
  if (xhr.status === 200) {
    console.log(xhr.response); // response will be in JSON format
  } else {
    console.error(xhr.statusText);
  }
};
xhr.send();

