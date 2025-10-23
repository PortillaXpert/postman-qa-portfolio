<div id="readme-top"></div>

<h1 align="center">API Testing Automation Portfolio</h1>
<p align="center">
  <img src="images/banner_api_portfolio.png" alt="QA Automation Banner" width="100%" />
</p>

<p align="center" class="lead">
  A complete portfolio of API testing automation projects built with <strong>Postman</strong>, <strong>Newman</strong>, and <strong>JavaScript</strong>.  
  Each collection represents a different level of professional QA practice — from RESTful CRUD validation to GraphQL and contract testing.
</p>

<p align="center">
  🔗 <strong>Explore the live collection on Postman:</strong><br/>
  <a href="https://www.postman.com/personal-qa-workspace/qa-portfolio" target="_blank">
    🌐 View Postman Workspace – QA Automation Portfolio
  </a>
</p>
<hr/>

<h2>Table of Contents</h2>
<ul>
  <li><a href="#overview">Overview</a></li>
  <li><a href="#collections">Collections</a></li>
  <li><a href="#technologies">Technologies Used</a></li>
  <li><a href="#how-to-run">How to Run</a></li>
  <li><a href="#coverage">Test Coverage & Metrics</a></li>
  <li><a href="#standards">Quality & Standards</a></li>
  <li><a href="#author">Author</a></li>
</ul>

<hr/>

<h2 id="overview">Overview</h2>
<p>
This portfolio showcases <strong>advanced API testing automation</strong> built using <strong>Postman</strong> and <strong>Newman CLI</strong>, following <strong>ISTQB-aligned methodologies</strong>.
Each collection focuses on a specific testing area:
</p>

<ul>
  <li><strong>RESTful CRUD Testing:</strong> Validates complete API lifecycle (create, read, update, delete)</li>
  <li><strong>E-commerce Workflow Automation:</strong> Simulates authentication, cart, and purchase flows</li>
  <li><strong>Contract Testing:</strong> Ensures JSON Schema compliance and backward compatibility</li>
  <li><strong>GraphQL Testing:</strong> Validates queries, mutations, variables, and fragments</li>
</ul>

<p>All projects include <strong>reusable scripts, assertions, dynamic variables,</strong> and are ready for CI/CD execution.</p>

<hr/>

<h2 id="collections">Collections</h2>

<h3>ReqRes API – Complete Testing Suite</h3>
<p>
Comprehensive RESTful testing collection demonstrating CRUD validation, dynamic chaining, and performance benchmarking.  
Applies ISTQB techniques such as Equivalence Partitioning, Boundary Value Analysis, and Error Guessing.
</p>

<ul>
  <li><strong>Requests:</strong> 23</li>
  <li><strong>Tests:</strong> 121+</li>
  <li><strong>Assertions:</strong> 187+</li>
  <li><strong>Coverage:</strong> Full CRUD + Workflow testing</li>
</ul>

---

<h3>DummyJSON E-commerce API – End-to-End Testing</h3>
<p>
Advanced e-commerce testing suite validating authentication, catalog operations, cart management, and purchase flows.  
Includes JWT token validation, request chaining, and business rule assertions.
</p>

<ul>
  <li><strong>Requests:</strong> 26</li>
  <li><strong>Tests:</strong> 186+</li>
  <li><strong>Modules:</strong> Auth, Users, Products, Cart, Workflows</li>
</ul>

---

<h3>Contract Testing & JSON Schema Validation</h3>
<p>
Ensures APIs comply with predefined contracts using <strong>Ajv</strong> and <strong>JSON Schema v7</strong>.  
Detects breaking changes, missing fields, and data type mismatches.
</p>

<ul>
  <li><strong>Requests:</strong> 3 (Users, Products, Carts)</li>
  <li><strong>Tests:</strong> 70+</li>
  <li><strong>Validations:</strong> Required fields, Enums, Ranges, Formats</li>
</ul>

---

<h3>GraphQL API Testing (New Collection)</h3>
<p>
Modern API testing approach using <strong>GraphQL</strong> queries, mutations, variables, and fragments.  
Demonstrates validation of complex nested data structures, response timing, and schema conformity.
</p>

<ul>
  <li><strong>Focus:</strong> Query & Mutation Testing</li>
  <li><strong>Features:</strong> Variables, Fragments, Type Checking, Error Handling</li>
</ul>

---

<h2 id="technologies">Technologies Used</h2>

<div align="center">

  <!--Main Tools-->
  <a href="https://www.postman.com/" target="_blank">
    <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
  </a>
  <a href="https://nodejs.org/" target="_blank">
    <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  </a>
  <a href="https://www.npmjs.com/package/newman" target="_blank">
    <img src="https://img.shields.io/badge/Newman-000000?style=for-the-badge&logo=npm&logoColor=white" alt="Newman" />
  </a>
  <a href="https://ajv.js.org/" target="_blank">
    <img src="https://img.shields.io/badge/AJV-004880?style=for-the-badge&logo=json&logoColor=white" alt="AJV" />
  </a>
  <a href="https://graphql.org/" target="_blank">
    <img src="https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white" alt="GraphQL" />
  </a>
  <a href="https://www.javascript.com/" target="_blank">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  </a>

  <!--Pipeline State-->
  <a href="https://github.com/PortillaXpert/postman-qa-portfolio/actions" target="_blank">
    <img src="https://img.shields.io/github/actions/workflow/status/PortillaXpert/postman-qa-portfolio/postman-tests.yml?style=for-the-badge&logo=githubactions&logoColor=white&label=CI%20Tests&color=2088FF" alt="GitHub Actions" />
  </a>

</div>

---

<h2 id="how-to-run">How to Run</h2>

<ol>
  <li>Clone this repository:
    <pre><code>git clone https://github.com/PortillaXpert/API-Testing-Automation-Portfolio.git</code></pre>
  </li>
  <li>Install <strong>Newman</strong>:
    <pre><code>npm install -g newman</code></pre>
  </li>
  <li>Run any collection:
    <pre><code>newman run ./collections/01_-_ReqRes_API_Testing.postman_collection.json -e ./environments/ReqRes_Production.postman_environment.json</code></pre>
  </li>
</ol>

---

<h2 id="coverage">Test Coverage & Metrics</h2>

| Collection | Requests | Tests | Assertions | Coverage |
|-------------|-----------|--------|-------------|-----------|
| ReqRes API | 23 | 121+ | 187+ | 100% CRUD |
| DummyJSON E-commerce | 26 | 186+ | 220+ | End-to-End Workflows |
| Contract Testing | 3 | 70+ | 100+ | Schema Compliance |
| GraphQL Testing | – | – | – | Query & Mutation Validation |

---

<h2 id="standards">Quality & Standards</h2>
<ul>
  <li>ISTQB-aligned design: EP, BVA, State Transition, Decision Table</li>
  <li>RESTful & GraphQL testing best practices</li>
  <li>Reusability through dynamic variables & environment configs</li>
  <li>Schema validation with Ajv (JSON Schema v7)</li>
  <li>CI/CD ready structure for Newman execution</li>
</ul>

---

<h2 id="author">Author</h2>
<p>
  Created by <a href="https://github.com/PortillaXpert" target="_blank"><strong>Juan Pablo Portilla</strong></a><br/>
  <em>QA Automation Engineer</em><br/>
  <a href="mailto:jrivera082002@gmail.com">jrivera082002@gmail.com</a> · 
  <a href="www.linkedin.com/in/juan-pablo-rivera-a90335374" target="_blank">LinkedIn</a>
</p>

<div align="right">
  (<a href="#readme-top">Back to top ↑</a>)
</div>
