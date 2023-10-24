tion = "Sway's AST"
authors.workspace = true
edition.workspace = true
homepage.workspace = true
license.workspace = true
repository.workspace = true

[dependencies]
extension-trait = "1.0.1"
num-bigint = { version = "0.4.3", features = ["serde"] }
num-traits = "0.2.14"
serde = { version = "1.0", features = ["derive"] }
extension-trait = "1.0.1"
num-bigint = { version = "0.4.3", features = ["serde"] }
num-traits = "0.2.14"
sway-error = { version = "0.46.1", path = "../sway-error" }
sway-types = { version = "0.46.1", path = "../sway-types" }
