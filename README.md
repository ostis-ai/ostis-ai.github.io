<div align="justify">

## Introduction

**OSTIS-AI** is an open-source initiative focused on developing and promoting **Open Semantic Technology for Intelligent Systems (OSTIS)**. This technology enables the creation of semantically compatible intelligent systems that can seamlessly integrate various types of knowledge and problem-solving models, allowing them to adapt and solve new problems efficiently.

---

## Why OSTIS?

OSTIS is not just another AI project; it's an open-source technology designed to revolutionize how we build intelligent systems. The primary goal of OSTIS is to address the limitations of current intelligent systems, which are often monolithic, difficult to modify, and expensive to develop.

By providing a universal framework for representing information using **SC-code (Semantic Computer code)**, OSTIS enables the creation of modular, reusable components that can be easily combined across different systems.

### Key Advantages of OSTIS:

- **Plug-and-Play Integration**: Seamlessly add new problem-solving models or knowledge without complex overhead.
- **Universal Components**: Reusable components reduce development time and effort across different systems.
- **Reflexivity**: Systems can analyze themselves, identify errors, and optimize performance – a hallmark of true intelligence.
- **Platform Independence**: ostis-systems can be implemented on various platforms, paving the way for semantic computers.
- **Parallel Processing**: Designed for efficient parallel information processing, especially beneficial for semantic computers.

### Key Features of SC-code:

- **Universality**: Represents any information uniformly.
- **Non-linearity**: Suitable for semantic associative computers.
- **Basic Alphabet**: Comprises just five elements.
- **Flexibility**: Can represent knowledge, models, and interfaces.

---

## Getting Started with OSTIS

To begin working with OSTIS, let's use the `ostis-example-app` as a practical starting point. This application demonstrates key components of an ostis-system, including a knowledge base, problem solver, and user interface.

### Step-by-Step Guide to ostis-example-app

1. Prerequisites:
   - Install Git: [https://git-scm.com/book/en/v2/Getting-Started-Installing-Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
   - Install Docker & Docker Compose: [https://www.docker.com/get-started](https://www.docker.com/get-started)

2. Clone Repository:
   
   ```sh
   git clone https://github.com/ostis-apps/ostis-example-app.git
   cd ostis-example-app
   git checkout 0.10.0
   git submodule update --init --recursive
   ```

3. Build Docker Images:
   
   ```sh
   docker compose build
   ```

4. Build Knowledge Base:
   
   ```sh
   docker compose run --rm machine build
   ```

5. Start System:
   
   ```sh
   docker compose up 
   # Access interface at http://localhost:8000/
   # To stop system use `docker compose stop`
   # Rebuild KB after changes in `.scs` or `.gwf` files 
   ```

6. To rebuild after changes in `.scs` or `.gwf`, repeat step 4.

---

## Contributing & Engaging with the Community

Join us by exploring these opportunities:

1. Join our Element Chat: [OSTIS Tech Support](https://app.element.io/#/room/#ostis_tech_support:matrix.org)  
2. Explore GitHub Repositories: [GitHub Repositories](https://github.com/ostis-ai)  
3. Attend OSTIS Conference: [OSTIS Conference](http://conf.ostis.net/en/ostis-conference/)  

We welcome your contributions! Use GitHub's issue tracker if you encounter issues or have suggestions.

</div>

--- 

Thank you for your interest in advancing OSTIS!
