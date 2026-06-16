# ⚙️ LUMINEX - Custom Programming Language & Compiler Design

A custom-engineered, lightweight programming language named **LUMINEX** (compiled with the `.nex` file extension) developed as a Compiler Construction project. The language is architected to bring absolute clarity, readability, and structural efficiency to language implementation concepts.

## 📐 Language Syntax & Regular Expressions (Regex)
The architecture specifies strict grammar rules, language lexemes, and regular expressions to govern tokenization and syntax parsing workflows:

* **Data Type Blueprint:** Supports explicit native data types including Integer (`num`), Float (`dec`), String (`str`), Character (`charact`), and Boolean (`boolit`).
* **Declaration & Initialization Rules:** Uses a dedicated `var` keyword combined with character validation bindings. 
  * *Regex Specification:* `var [a-zA-Z][a-zA-Z0-9]* : (int|float|string|bool)<.*>;`
* **Control Flow Automation:** Defines explicit syntax patterns for conditional branches including standard `if`, `else if`, and fallback `else` blocks.
* **Function Definition Grammar:** Implements rigorous function signature parameters mapping parameters directly to return outputs.
  * *Regex Specification:* `func [a-zA-Z][a-zA-Z0-9]* ([a-zA-Z][a-zA-Z0-9]* : int|float|string|bool) -> (int|float|string|bool) {*}`

## 🛡️ Cybersecurity & Malware Analysis Relevance
* **Automated Threat Detection Signatures:** Designing tokenizers and regular expressions mirrors how static security tools analyze software pipelines. Understanding lexical token matches is fundamental when building complex YARA rules or custom regex patterns to catch polymorphic malware signatures inside security log collectors.
* **Syntax Injection Defenses:** Deep compiler parsing knowledge helps secure input sanitation, preventing attackers from executing code or parameter injection strategies (like SQLi or Remote Code Execution) against production parsing engines.

## 🛠️ Technical Focus
* **Concepts:** Compiler Construction, Lexical Analysis, Tokenization, Grammar Rules, Regular Expressions (Regex)
* **Syntax Structures:** Strict static typing models, variable initialization parameters, conditional logic trees, and functional definitions.
