### Montar

```bash
mkdir EXAME_DEC && gocryptfs EXAME_ENC EXAME_DEC
```
### Desmontar
```bash
fuser -km EXAME_DEC && sudo fuser umount && sudo rm -rf EXAME_DEC
```
