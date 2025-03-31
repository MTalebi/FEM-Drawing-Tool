# Professional Structural FEM Drawing App

This **React + Konva** application allows you to interactively create structural finite element (FE) models. You can easily place **nodes**, define **members** (beam or truss), specify **supports** (fixed, roller-x, roller-y, hinge), and assign **loads** (point, uniform, nonuniform). The app then **organizes** all geometry and properties into a **structured JSON** output that can be used in frameworks like **OpenSeesPy** or other open-source FE modeling tools.

---

## Key Features

- **Node Placement**  
  Click anywhere on the canvas to place nodes. Optionally enable grid snapping to keep them aligned at user-defined intervals.
  
- **Member Creation**  
  Pick two nodes to form a member. Choose **beam** or **truss**.  
  \> *Truss members automatically skip distributed loads to reflect real-world behavior.*

- **Support Definition**  
  Quickly assign fixed, roller-x, roller-y, or hinge supports to any node.

- **Load Assignment**  
  - **Point Load**: Attach forces directly to nodes.  
  - **Uniform Distributed Load**: Place a uniform load along a beam member.  
  - **Nonuniform Distributed Load**: Linearly varying load from start to end.  
  \> *Automated skipping of distributed loads on truss members ensures consistency.*

- **Interactive UI**  
  - **Grid Snap**: Toggle grid snapping and specify spacing.  
  - **Undo**: Revert your last action.  
  - **Clear All**: Start a fresh model.  
  - **Save**: Export your entire FE model in structured JSON.

- **Export to JSON**  
  The exported JSON is easily parsed by **OpenSeesPy** or similar FE frameworks, letting you focus on **analysis** rather than model geometry definition.

---
## Contact

Authored by **Mohammad Talebi-Kalaleh**  
Email: [talebika@ualberta.ca](mailto:talebika@ualberta.ca)  
Website & more structural engineering tools: [mtalebi.com](https://mtalebi.com)

Feel free to reach out with questions, feedback, or suggestions to improve this open-source FE modeling assistant.
```
