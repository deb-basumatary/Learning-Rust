### Install Rust in Linux  & MacOS
```sh
$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
```
To check whether you have Rust installed correctly, open a shell and enter this line:
```sh
$ rustc --version
```
### Update & Uninstall 
Once Rust is installed via `rustup`, updating to a newly released version is easy. From your shell, run the following update script:

```sh 
$ rustup update
```
To uninstall Rust and `rustup`, run the following uninstall script from your shell:

```sh
$ rustup self uninstall
```
### [Reading the Local Documentation](https://rust-book.cs.brown.edu/ch01-01-installation.html#reading-the-local-documentation)

The installation of Rust also includes a local copy of the documentation so that you can read it offline. Run `rustup doc` to open the local documentation in your browser.

### Create a new Rust Project
```sh
$ cargo new <project-name>
```
