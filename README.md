# My Yew app
## Getting started
<ol>
    <li>Create a workspace and clone the project</li>
    <code>git clone https://github.com/MarkusHenriks1/yew-app.git</code>
     <li><code>cd yew-app</code></li>
    <li>Now install rust using rustup <a href="https://www.rust-lang.org/tools/install">install rust</a> </li>
    <li>Now install trunk using cargo <code>cargo install trunk</code></li>
    <li>Then add the WASM build target <code>rustup target add wasm32-unknown-unknown</code></li>
    <li>Run the command <code>cargo build</code></li>
    <li>Run the command <code>cargo run</code></li>
    <li>If both ran ok, then serve up the application with  <code>trunk serve --open</code></li>
    <li>The app is now available on <a href="127.0.0.1:8080">127.0.0.1:8080</a></li>
    <li>Find more information here:</li>
    <a href="https://yew.rs/docs/tutorial">https://yew.rs/docs/tutorial</a>
</ol>


## Happy hacking!