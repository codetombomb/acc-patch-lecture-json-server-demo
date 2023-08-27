# acc-patch-lecture-json-server-demo

🔥🔥🔥 CODE DEMO! 🔥🔥🔥
    
- Create `db.json` file
- Add the following data
    - Fake JSON data:
            
            ```json
            {
              "programmers": [
                {
                  "id": 1,
                  "name": "Ada Lovelace",
                  "birth_year": 1815,
                  "contributions": [
                    "Wrote the world's first algorithm intended to be processed by a machine (Analytical Engine).",
                    "Considered the first computer programmer."
                  ]
                },
                {
                  "id": 2,
                  "name": "Alan Turing",
                  "birth_year": 1912,
                  "contributions": [
                    "Developed the Turing machine, a fundamental concept in computer science.",
                    "Played a key role in breaking the Enigma code during World War II.",
                    "Laid the foundation for modern computer science and artificial intelligence."
                  ]
                },
                {
                  "id": 3,
                  "name": "Grace Hopper",
                  "birth_year": 1906,
                  "contributions": [
                    "Developed the first compiler for a programming language (COBOL).",
                    "Coined the term 'bug' in the context of computer programming."
                  ]
                },
                {
                  "id": 4,
                  "name": "Linus Torvalds",
                  "birth_year": 1969,
                  "contributions": [
                    "Created the Linux operating system kernel.",
                    "Pioneered the open-source software development model."
                  ]
                },
                {
                  "id": 5,
                  "name": "John McCarthy",
                  "birth_year": 1927,
                  "contributions": [
                    "Invented the Lisp programming language.",
                    "Coined the term 'artificial intelligence.'"
                  ]
                },
                {
                  "id": 6,
                  "name": "Tim Berners-Lee",
                  "birth_year": 1955,
                  "contributions": [
                    "Invented the World Wide Web (WWW).",
                    "Developed the first web browser and web server software."
                  ]
                },
                {
                  "id": 7,
                  "name": "Margaret Hamilton",
                  "birth_year": 1936,
                  "contributions": [
                    "Led the team that developed software for the Apollo moon missions.",
                    "Coined the term 'software engineering.'"
                  ]
                },
                {
                  "id": 8,
                  "name": "Donald Knuth",
                  "birth_year": 1938,
                  "contributions": [
                    "Authored 'The Art of Computer Programming' series, a seminal work in computer science.",
                    "Developed TeX typesetting system."
                  ]
                },
                {
                  "id": 9,
                  "name": "Dennis Ritchie",
                  "birth_year": 1941,
                  "contributions": [
                    "Co-created the C programming language.",
                    "Contributed to the development of Unix operating system."
                  ]
                },
                {
                  "id": 10,
                  "name": "Ada Lovelace II",
                  "birth_year": 1970,
                  "contributions": [
                    "Advanced AI research with novel algorithms for machine learning.",
                    "Pioneered the use of neural networks for natural language processing."
                  ]
                },
                {
                  "id": 11,
                  "name": "Yukihiro Matsumoto",
                  "birth_year": 1965,
                  "contributions": [
                    "Created the Ruby programming language, known for its elegance and productivity."
                  ]
                },
                {
                  "id": 12,
                  "name": "Guido van Rossum",
                  "birth_year": 1956,
                  "contributions": [
                    "Invented the Python programming language.",
                    "Promoted a philosophy of code readability and simplicity."
                  ]
                },
                {
                  "id": 13,
                  "name": "Sheryl Wang",
                  "birth_year": 1980,
                  "contributions": [
                    "Led groundbreaking research in quantum computing algorithms.",
                    "Developed algorithms for efficient encryption techniques."
                  ]
                },
                {
                  "id": 14,
                  "name": "Hiroshi Suzuki",
                  "birth_year": 1990,
                  "contributions": [
                    "Advanced the field of artificial intelligence with deep learning models.",
                    "Co-authored the influential 'Suzuki-Net' neural network architecture."
                  ]
                },
                {
                  "id": 15,
                  "name": "Maria Lopez",
                  "birth_year": 1982,
                  "contributions": [
                    "Revolutionized cybersecurity with innovative intrusion detection algorithms.",
                    "Developed the 'Lopez Firewall' for network protection."
                  ]
                },
                {
                  "id": 16,
                  "name": "Raj Patel",
                  "birth_year": 1974,
                  "contributions": [
                    "Contributed to the development of distributed systems and cloud computing.",
                    "Authored influential papers on scalable infrastructure."
                  ]
                },
                {
                  "id": 17,
                  "name": "Olivia Chen",
                  "birth_year": 1988,
                  "contributions": [
                    "Pioneered advancements in machine learning for healthcare applications.",
                    "Developed AI models for early disease detection."
                  ]
                },
                {
                  "id": 18,
                  "name": "Samuel White",
                  "birth_year": 1960,
                  "contributions": [
                    "Made significant contributions to the field of robotics and automation.",
                    "Invented the 'WhiteBot' series of autonomous robots."
                  ]
                },
                {
                  "id": 19,
                  "name": "Ella Davis",
                  "birth_year": 1978,
                  "contributions": [
                    "Advanced the field of natural language processing with novel algorithms.",
                    "Developed conversational AI systems for human-computer interaction."
                  ]
                },
                {
                  "id": 20,
                  "name": "Martin Schmidt",
                  "birth_year": 1995,
                  "contributions": [
                    "Pioneered the development of decentralized blockchain technologies.",
                    "Authored the 'SchmidtChain' consensus algorithm."
                  ]
                }
              ]
            }
            ```
            
    - Use POSTMAN to:
        - GET all data
        - Add another resource - users - and get all users
    - Take a look at the [json-server docs](https://github.com/typicode/json-server#getting-started) and demo:
        - [Pagination](https://github.com/typicode/json-server#getting-started)
            - `?_page=3&_limit=2`
        - [Sort](https://github.com/typicode/json-server#sort)
            - `?_sort=id&_order=desc`
        - [Slice](https://github.com/typicode/json-server#slice)
            - `?_start=2&_end=3`
            
- [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/fetch#syntax)
    - Write a get request
    - Write a post request
        - discuss the config object
