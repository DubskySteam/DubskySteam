# 💻 Current Toolbox

### **🛠️ Primary Tools**
<p>
  <img src="https://img.shields.io/badge/NeoVim-%2357A143.svg?style=for-the-badge&logo=neovim&logoColor=white">
  <img src="https://img.shields.io/badge/JetBrains-000000?style=for-the-badge&logo=jetbrains&logoColor=white">
</p>

### **⌨️ Terminal Setup**
<p>
  <img src="https://img.shields.io/badge/WezTerm-000000?style=for-the-badge&logo=wezterm&logoColor=white">
  <img src="https://img.shields.io/badge/tmux-1BB91F?style=for-the-badge&logo=tmux&logoColor=white">
</p>

### **💾 Languages**
<p>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white">
  <img src="https://img.shields.io/badge/Zig-F7A41D?style=for-the-badge&logo=zig&logoColor=white">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black">
</p>

### **🖥️ Operating Systems**
<p>
  <img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white">
  <a href="https://github.com/DubskySteam/WinFlux" target="_blank"><img src="https://img.shields.io/badge/WinFlux-0078D4?style=for-the-badge&logo=windows11&logoColor=white"></a>
</p>

---

### **🚀 Current Projects**
```rust
struct Project {
    name: &'static str,
    description: &'static str,
}

fn main() {
    let projects = vec![
        Project { name: "Aiko", description: "Cross-plattform desktop app for Anime" },
        Project { name: "Workflow", description: "Optimizing my workspace and workflows" },
        Project { name: "Kernel", description: "Learning about kernel development" },
        Project { name: "Embedded", description: "Diving more into embedded systems" },
    ];
    
    println!("Current Projects:");
    for project in projects {
        println!("• {} - {}", project.name, project.description);
    }
}
