# homebrew-rosen

Tap do Homebrew para o [Rosen](https://github.com/bellinivitor/rosen), gerenciador nativo de túneis SSH para macOS.

```bash
brew install --cask bellinivitor/rosen/rosen
```

Na primeira abertura, como o app ainda não é assinado com certificado Apple:

```bash
xattr -dr com.apple.quarantine /Applications/Rosen.app
```

O Cask é atualizado automaticamente a cada release do Rosen.
