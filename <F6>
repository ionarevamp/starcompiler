use std::io::{self, Write};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    match writeln!(io::stdout(), "Hello, world!") {
        Ok(_) => { () },
        Err(e) => return Err(Box::new(e)),
    };

    let _testnum = 42i32 - 30u32;

    Ok(())
}
