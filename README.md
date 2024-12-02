# Project Overview 👨🏻‍⚖️✨

This project focuses on simulating **civil court proceedings** in a courtroom-like setting. The primary goal is to replicate a structured legal process, facilitating arguments between plaintiff and defendant advocates based on provided evidence, witness statements, and legal issues framed by a simulated judge. It serves as a **proof-of-concept** that demonstrates how court proceedings can be simulated effectively with the right amount of accurate inputs.

## Key Features 🛠️

### 1. **Legal Process Simulation ⚖️**
The model emulates an entire courtroom scenario, starting from filing the plaint to the resolution of arguments. Advocates examine and cross-examine witnesses, present evidence, and respond to counterpoints. **Integrated tools** allow interactions with witnesses, opposing advocates, and the Civil Procedure Code (CPC), ensuring a realistic and structured flow of events.

---

### 2. **Large-Scale Input Management 📜**
Legal proceedings involve **voluminous documentation** such as agreements, statements, procedural codes, and evidence. This project overcomes the challenge of processing inputs exceeding token limits by using **chunking and memory management techniques**. For instance, the CPC master tool alone handles over **300,000 tokens**, guiding the process with detailed procedural insights throughout the simulation.

---

### 3. **Role-Playing with Models 🎭**
Each model in the system plays a specific role:
   - **Advocates**: Represent their respective parties (plaintiff and defendant). 👨‍💼👩‍💼  
   - **Witnesses**: Respond to examination and cross-examination. 🗣️  
   - **Judge**: Frames issues, monitors arguments, and ensures procedural compliance. ⚖️

An additional **Cross-Facilitator Model** enables smooth interaction between the two advocate models, ensuring coherent and structured arguments. This setup brings life to the legal discourse, making the simulation both engaging and interactive.

---

### 4. **Dynamic Argument Flow 🔄**
The advocates engage in detailed, **realistic back-and-forth discussions**, presenting their strongest arguments, questioning witnesses, and addressing legal issues step-by-step. The simulation mirrors real-life courtroom proceedings, complete with procedural depth and spontaneity. Observing the advocate models argue and counter each other, often with surprising strategies, brings an **entertaining yet educational aspect** akin to legal dramas portrayed in movies. 🎬

---

### 5. **Structured Output 📊**
At the conclusion of the proceedings, the project generates a **comprehensive summary** of the argument:
   - Questions asked and responses provided. ❓🗨️  
   - Issues raised and resolved. ⚙️  
   - Witness testimonies and evidence debated. 📝

This structured output offers a detailed record of the case, making it useful for legal education, analysis, or even as a foundation for building AI-assisted legal research tools. 🔍

---

## Why It Matters 💡
This project showcases the potential of AI in the legal domain, proving that complex judicial processes can be simulated and analyzed. It opens doors for:
- **Legal education**: Helping students and professionals understand courtroom dynamics. 🎓  
- **Case preparation**: Assisting lawyers in testing arguments and strategies. 🧑‍⚖️  
- **Access to justice**: Providing an innovative tool to demystify legal procedures for the public. 🤝  

By demonstrating the seamless handling of large-scale inputs and fostering realistic role-playing, this project proves that **AI can enhance and transform the legal field**. 🚀

## Flowchart of how civil proceedings happen in Indian courts.
![full-flow](https://github.com/user-attachments/assets/0ca0d3bd-fa0a-4229-9d04-c8c202bcacc7)


## Derived flow for simplicity of flow
![derived-flow](https://github.com/user-attachments/assets/2cfe366d-4e23-42fc-96b2-95527ddfc015)


## Details of the flow
![flow](https://github.com/user-attachments/assets/db6f5a9b-1397-4992-8f60-d499afbd59ff)


