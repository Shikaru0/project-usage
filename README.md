# project-usage

Base structure:

## Project

### Initialization

### Layout

### Running

### Dependencies

### Formatting

### Checking

### Linting

### Testing

### Building

### Documentation

### Maintenance

## Cargo - Rust

### Initialization
Create a new directory:
```
cargo new project-name
```
Initialize in existing directory:
```
cargo init
```

### Layout

### Running
```
cargo run
```

### Dependencies
Adding a dependency:
```
cargo add dependency-name
```

Removing a dependency:
```
cargo remove dependency-name
```

### Formatting
```
cargo fmt
```

### Checking
```
cargo check
```

### Linting
```
cargo clippy
```

### Testing
```
cargo test
```

### Building
Debug build:
```
cargo build
```
Release:
```
cargo build --release
```

### Documentation
```
cargo doc
```

### Maintenance
```
cargo update
```

## Bun - TS/JS runtime

### Initialization
Initialize in existing directory:
```
bun init #-y
```

### Layout

### Running
In package.json you can configure scripts, with an entry point, for instance

`"main": "bun src/index.ts"`

which allows you do do
`bun run main`

```
bun run entrypoint
```

### Dependencies
Adding a dependency:
```
bun add dependency-name
```

Removing a dependency:
```
bun remove dependency-name
```

Adding a dev dependency
```
bun add -D dependency-name
```

### Formatting
```
```

### Checking
```
```

### Linting
```
```

### Testing
```
```

### Building
Debug build:
```
```
Release:
```
```

### Documentation
```
```

### Maintenance
```
```

