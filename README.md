# MacOS terminal cheatsheet 

**NOTE:** cheatsheet jsem si vytvoril pro sebe jako souhrn castych commandu, ktere bezne pouzivam, abych si je mohl rychle dohledavat, takze zde commandy nejak moc vyrazne nekomentuji ci nevysvetluji, nebot to neni vyznam tohoto meho cheatsheetu. 

## Globalni konfiguracni soubor:

Otevreni pres `nano`:
```
nano ~/.zshrc
```

Pro okamzite ulozeni a nacteni zmen v `~/.zshrc` musim spustit command:
```
source ~/.zshrc
```

## Anaconda pro spravu balicku

For activation prostredi:

```
conda activate ml1
```
Pro vypsani vsech knihovne v prostredi (prostredi musi byt aktivovane)

```
conda list
```
Pro vypsani vsech prostredi:

```
conda env list
```
vypnuti prostredi:

```
conda deactivate
```
Pro instalaci nejake lib (napr. `polars`) musim mit jiz aktivovane prostredi:
```
conda install polars
```

## Git (mam soubor lokalne a chci hodit na repo)

```
git init
git add remote origin git@github.com:staifmatej/bi-pa2.gitxy
git pull origin main --no-rebase --allow-unrelated-histories
gpush
```
**NOTE:**
