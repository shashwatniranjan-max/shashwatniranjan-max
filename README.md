```rust
struct Developer {
    name: &'static str,
    role: &'static str,
    focus_areas: [&'static str; 4],
    secondary_interests: [&'static str; 2],
    current_goal: &'static str
}

fn main() {
    let me = Developer {
        name: "Shashwat Niranjan",
        role: "Full Stack Developer (MERN) & Python Enthusiast",
        focus_areas: ["Node.js", "Express.js", "React", "TypeScript"],
        secondary_interests: ["Python/FastAPI", "Web3"],
        current_goal: "Google Summer of Code 2026"
    };

    println!("Hello, I'm {}.", me.name);
    println!("I'm a {} building for the modern web.", me.role);
    println!("My current mission: {}.", me.current_goal);
}


🚀 I'm currently on an intensive deep-dive into the MERN stack, building a solid foundation from HTTP servers to full-stack applications.

🎯 My primary goal for early 2026 is to become a high-impact open-source contributor and get selected for GSoC.

🌱 I'm documenting my progress and challenges in my Learning Log repository as I work through my goals.

♟️ P.S. When I'm not coding, you can usually find me planning my next move in a game of chess.

