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

## Apoie

Se este projeto te ajudou, você pode me pagar um café ☕

<a href="https://buymeacoffee.com/vitorbellini"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" height="40"></a>
