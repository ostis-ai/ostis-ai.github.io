### Introduction

OSTIS-AI is an open-source initiative dedicated to developing and promoting **Open Semantic Technology for Intelligent Systems** (**OSTIS**). This technology aims to create semantically compatible intelligent systems that can seamlessly integrate various types of knowledge and problem-solving models, enabling them to adapt and solve new problems efficiently.

### Why OSTIS?

OSTIS (Open Semantic Technology for Intelligent Systems) isn't just another AI project; it's an open-source technology designed to revolutionize how we build intelligent systems. 

The primary goal of OSTIS is to address the limitations of current intelligent systems, which are often monolithic, difficult to modify, and expensive to develop. By providing a universal framework for representing information using **SC-code** (Semantic Computer Code), OSTIS enables the creation of modular, reusable components that can be easily combined across different systems.

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

### Getting Started with OSTIS

To begin working with OSTIS, let's use the `ostis-example-app` as a practical starting point. This application demonstrates key components of an ostis-system, including a knowledge base, problem solver, and user interface.

### Step-by-Step Guide to `ostis-example-app`

1. **Prerequisites**:
   
   - [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) for cloning repositories.
   - [Install Docker and Docker Compose](https://www.docker.com/get-started) for simplified setup.

2. **Clone the Repository**:
   
   ```sh
   git clone https://github.com/ostis-apps/ostis-example-app.git
   cd ostis-example-app
   git checkout 0.10.0
   git submodule update --init --recursive
   ```

3. **Build Docker Images**:
   
   ```sh
   docker compose build
   ```

4. **Build Knowledge Base**:
   
   ```sh
   docker compose run --rm machine build
   ```

5. **Start the System**:
   
   ```sh
   docker compose up # Accessible at localhost:8000.
   ```
   
6. To stop the system, use `docker compose stop`.
   
7. Rebuild the knowledge base after any changes to `.scs` or `.gwf` files.

### Contributing to and Engaging with the OSTIS Community

To become part of the OSTIS community and contribute, you can use the following opportunities:

- **Join our Element Chat:** [OSTIS Tech Support](https://app.element.io/#/room/#ostis_tech_support:matrix.org) for real-time support and discussions.
- **Explore our GitHub Repositories:** [GitHub Repositories](https://github.com/ostis-ai), where you can familiarize yourself with projects and participate in their development.
- **Attend the OSTIS Conference:** [OSTIS Conference](http://conf.ostis.net/en/ostis-conference/) to learn about the latest advancements and share your experiences.

**We welcome your contributions**! If you encounter issues or have suggestions for new features, please use the issue tracker system on each project's repository page on GitHub.

---

Thank you for your interest in advancing OSTIS with us!
