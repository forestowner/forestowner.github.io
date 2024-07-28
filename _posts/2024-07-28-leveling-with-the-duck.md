# Welcome to My Blog!

```tsql
-- Introduction
DECLARE @Intro NVARCHAR(MAX) = 
    'Hello, everyone! My name is Hanna Nyzhnia, and I was born in Kyiv. From a young age, I developed a passion for programming and technology, which led me to pursue a degree in this exciting field. During my university years, I honed my skills as a designer, which has greatly influenced my approach to front-end development. 

    After graduation, I began my professional journey as a QA tester in the telecommunications industry. I then transitioned into a role as a cybersecurity consultant, where I obtained my Master’s degree in Cybersecurity. 

    My career took a significant turn when I moved to the USA to work as a full-stack developer at two innovative startups. This journey has been incredibly fulfilling, and I am excited to share my experiences and insights through this blog.';

-- Congratulatory Message
DECLARE @Congrats NVARCHAR(MAX) = 
    'I am thrilled to welcome you all to my first blog post! This platform will serve as a space for me to share my knowledge, experiences, and tips on various topics related to technology, programming, cybersecurity, and much more. Stay tuned for more exciting content!';

-- Print Introduction and Congratulatory Message
PRINT @Intro;
PRINT @Congrats;
