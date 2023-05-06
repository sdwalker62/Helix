# Helix Dotfiles

The files contained within this config are ready to deploy. For the language servers run the following commands, choosing the language
servers you require.

---

# Language Servers

## Python
```bash
pip install -U 'python-lsp-server[all]'
```

## C++
```bash
sudo apt-get install clangd-12
```

## CMake
```bash
pip install cmake-language-server
```

Other language servers can be found in the documentation:
https://github.com/helix-editor/helix/wiki/How-to-install-the-default-language-servers#markdoc