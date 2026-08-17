# 🧭 Welcome to the Rhumb Language Organization

### What is Rhumb?

Rhumb is a dynamically-typed reactive multi-paradigm programming language. Taking deep inspiration from Self and JavaScript, Rhumb introduces a unique approach to object-oriented and concurrent programming.

### 📐 Design Philosophy

Rhumb is designed to be exotic compared to traditional programming concepts while retaining a familiar ALGOL-style procedural structure.

* There are no statements in Rhumb; everything is an expression. All of the statement and keyword-based functionality found in traditional programming languages is exclusively covered by operators and expressions.
* Rhumb relies on a prototype-based object model where the fundamental object is the **Map**. Maps are not created through classes but are interacted with by cloning or using subroutine constructors.
* Behind the scenes, maps use a hidden class called a "Legend" to define structural layout.
* Maps can have multiple parents via subfields, creating a Directed Acyclic Graph (DAG) structured object system that supports multiple inheritance and traits.

### ⚡ Concurrency & State Management

Rhumb completely replaces the traditional Call Stack with a spatial metaphor.

* Concurrency, event handling, and state management are unified into a Hierarchical Tuplespace driven by the **Syndicated Actor Model (SAM)**.
* Tuplespaces are called "Realms," and the language uses "Selectors" to act as Algebraic Effect handlers.
* Concurrency primitives (like Signals, Replies, and Proclamations) work identically across local and remote network boundaries.

### 🛠️ Architecture & Tooling

* The Rhumb Virtual Machine is written in Odin and operates on a strict 64-bit IEEE-754 NaN-boxing architecture to ensure blazing-fast execution speeds.
* By treating the file system itself as the configuration layer, Rhumb provides an intuitive way to build powerful command-line tools.
* External dependencies are managed via Catalog files (`.rhy`), which act as both the dependency manifest and an integrity anchor. Every dependency requires a cryptographic checksum (Anchor) to prevent malicious updates or "Left-Pad" incidents.

### 🚀 Getting Started

Rhumb is currently a work in progress. You can get a copy of the source code and contribute to the core Virtual Machine by cloning the main repository:

* 🔗 **[TBD](https://github.com/rhumb-lang)**
