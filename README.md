<span color='#a61f0a'>*r4in_*</span><span color='#04cc2f'>*@*</span><span color='#0a55a6'>*desktop*</span> ~/me → <span color='#0a74c4'>cat</span> <span color='#0ac464'>**src/main.rs**</span>
```rust
fn main(){
    let whoami =  json::object!{
        age: "Undefined",
        activity: "IT Student / Backpacker",
        blog: "r4in.xyz",
        email: "contact@r4in.xyz",
        projects: "Not Found...",
        hobbies: ["Climbing", "Photography","..."],
    };

    let platforms = json::object!{
        rootme: "https://www.root-me.org/r4in_",
        thm: "https://tryhackme.com/r/p/0xr4in",
        mastodon: "@r4in@defcon.social"
    };

    println!("👋 Welcome to my profile !");
    println!("🎓 I'm an {}", whoami["activity"]);
    println!("🌐 Blog : {}", whoami["blog"]);
    println!("🛠️ I'm currrenly working on {}", whoami["projects"]);
    println!("📝 And currently learning Rust 🦀");
    println!("📩 You can reach at {} ", whoami["email"]);
    println!("🐘 Or on mastodon {}", platforms["mastodon"]);
} 

```
