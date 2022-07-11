# Changelog

All notable changes to this project will be documented in this file.

## [HEAD](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.35.2...HEAD)

### ✨ Features

- Add TTC format 👉 https://github.com/jonz94/ttc-sarasa-gothic-nerd-fonts

## [v0.35.2](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.35.1...v0.35.2) (2021-11-28)

### ⚠ BREAKING CHANGES / ✨ Features

- In previous version, all variants of the patched fonts have exact same TTF font family name `Sarasa Nerd Font`. Now, each variant of the patched fonts will have proper TTF font family name. See [List of TTF Font Family Name](docs/ttf-font-family-name.md) for more details.

- You will need to apply changes to the font setting of the application after updating fonts to this version. For example: in order to using newer version of `sarasa-mono-tc-nerd-font.zip` in vscode, apply the following changes to vscode's `settings.json`:

```diff
-  "editor.fontFamily": "Sarasa Nerd Font",
+  "editor.fontFamily": "Sarasa Mono TC Nerd Font",
```

### ✅ Bug Fixes

- Resolve font alignment issue ([145000b](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/145000bf0a64ae0bf17b99e483fb40e414ef6cad)), closes [#1](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/issues/1)
- Correct TTF font family name ([339054a](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/339054a9d8c3a70d61abbe60f857031ade8cfee4)), closes [#2](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/issues/2)

## [v0.35.0](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.34.7...v0.35.0) (2021-11-08)

### ✨ Features

- Support [Homebrew](https://brew.sh) by creating custom homebrew tap 👉 https://github.com/jonz94/homebrew-sarasa-nerd-fonts

## [v0.34.7](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.34.6...v0.34.7) (2021-10-24)

### ⚠ BREAKING CHANGES

- The scoop bucket part is now moving to its own repository 👉 https://github.com/jonz94/scoop-sarasa-nerd-fonts ([e918116](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/e9181166332ef7d858aff69577f5c5c7bb52441c))

## [v0.34.2](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.34.1...v0.34.2) (2021-08-31)

### ✨ Features

- Now all the font styles (`fixed`, `fixed-slab`, `mono`, `mono-slab`, `term`, `term-slab`, `gothic`, `ui`) and orthographies (`cl`, `hc`, `j`, `k`, `sc`, `tc`) of Sarasa Gothic is being patched ([47c74a5](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/47c74a580cbb332b81104f8db6b4c44729b6d125))

## [v0.32.14](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.32.13...v0.32.14) (2021-07-25)

### ⚠ BREAKING CHANGES

- The release page now provide **a single `sarasa-mono-tc-nerd-font.zip` file includes all the font variants**, instead of a `.ttf` font file named `Sarasa-Mono-TC-Nerd-Font-Complete.ttf` in previous versions (`v0.32.13` and below)

### ✨ Features

- Now all the font variants (`Regular`, `Italic`, `Bold`, `Bold Italic`, `Light`, `Light Italic`, `Semibold`, `Semibold Italic`, `ExtraXlight`, `Extralight Italic`) of Sarasa Mono TC is being patched ([4cbe8b9](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/4cbe8b964e618d559adcf6e9eaac9d6c0432a828))
