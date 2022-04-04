
# minigrep

A simple grep-like CLI built in Rust, just for fun.
## Run Locally

Clone the project

```bash
  git clone https://github.com/bryan-matheus/minigrep.git
```

Go to the project directory

```bash
  cd minigrep
```

Install dependencies

```bash
  cargo build
```

Start the app

```bash
  cargo run <term> <file>
```


## Environment Variables

If you want to run a case insensitive search you will need this environment variable:

`CASE_SENSITIVE = true`


## Usage / Examples

Test with the current test file under the root of the app.

```bash
  cargo run frog poem.txt

```

For case insensitive search we need to export environment variable

```bash
  export CASE_SENSITIVE=true

```

Then:

```bash
  cargo run frog poem.txt

```

And don't forget to unset the environment variable after use

```bash
  unset CASE_SENSITIVE

```
## Tech Stack

Rust!
