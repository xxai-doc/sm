<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

E fautuaina e faʻapipiʻi nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) muamua, ona `direnv allow` pe a uma ona ulufale i totonu o le lisi ( [o le .envrc](https://github.com/xxai-art/doc/blob/main/.envrc) o le a faʻataunuʻuina otometi pe a uma ona ulufale i le lisi).

O lona uiga: Fa'aliliuga Saina i le gagana Iapani, Korea, Igilisi, fa'aliliuga Igilisi i isi gagana uma. Afai e te manaʻo e lagolagoina le gagana Saina ma le Igilisi, e mafai ona e tusi `zh: en` .

O lona uiga: Fa'aliliuga Saina i le gagana Iapani, Korea, Igilisi, fa'aliliuga Igilisi i isi gagana uma. Afai e te manaʻo e lagolagoina le gagana Saina ma le Igilisi, e mafai ona e tusi `zh: en` .

* [code pito i luma](https://github.com/xxai-art/web)
* [Gagana mo le saite atoa](https://github.com/xxai-art/web/tree/main/i18n)
* [Fa'aupuga gagana mo modules saini](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Upega Tafa'ilagi Fa'amaumauga e tele gagana](https://github.com/xxai-doc)

O le gagana faʻapolokalame pito i luma o le [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) , lea e faʻaopoopoina ai nisi o foliga faʻavae i luga o le kopi kopi kopi, vaʻai [./coffee_plus.md](./coffee_plus.md) .

## Fa'ava-o-malo o upegatafa'ilagi ma pepa

Fausia i luga ole 3 galuega faatino nei

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  O le suffix o `.mdt` , e mafai ona e faʻaogaina le syntax e tutusa ma `<+ ./coffee_plus/import.js>` e faʻasino i faila i fafo, ma faʻatupu le faʻailoga faʻatasi ma le suffix `.md` .

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  Fa'aliliuga Markdown o le a le fa'aliliuina tulafono laiti ma so'oga, ma o le a natia fa'aliliuga fuaiupu. Afai e suia le faaliliuga ae e le o suia le uluai tusitusiga, o le toe faia o le a le toe suia ai le suiga o le faaliliuga.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  Gagana faila mo le fa'aliliuina o upegatafa'ilagi faia `yaml` .

### Fa'atonuga Fa'aliliuga Fa'amaumauga

Va'ai fa'ailoga fa'ailoga [xxai-art/doc](https://github.com/xxai-art/doc)

E fautuaina e faʻapipiʻi nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) muamua, ona `direnv allow` pe a uma ona ulufale i totonu o le lisi ( [o le .envrc](https://github.com/xxai-art/doc/blob/main/.envrc) o le a faʻataunuʻuina otometi pe a uma ona ulufale i le lisi).

Ina ia aloese mai le tele o code base ua faaliliuina i le faitau selau o gagana, na ou faia ai se isi code base mo gagana taitasi ma faia se faalapotopotoga e teu ai le code base

Fa'atulaga le si'osi'omaga fesuia'i `GITHUB_ACCESS_TOKEN` ona tamoe lea [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) o le a otometi lava ona fatuina le fa'aputuga code.

Ioe, e mafai foi ona e tuʻuina i totonu o se faʻavae code.

Fa'aliliuga tusitusiga fa'asino [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

O le code code o loʻo faʻamatalaina e faapea:

[bunx](https://bun.sh/docs/cli/bunx) o se sui mo le npx, lea e vave. Ioe, afai e leai sau bun faʻapipiʻi, e mafai ona e faʻaogaina `npx` nai lo.

`bunx mdt zh` renders `.mdt` i le zh directory pei `.md` , va'ai le 2 feso'ota'i faila i lalo

* [coffee_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [coffee_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` o le fa'ailoga autu mo le fa'aliliuga (pe a na'o `nodejs` fa'apipi'i, ae le fa'apipi'i `bun` ma `direnv` , e mafai fo'i ona e ta'e `npx i18n` e fa'aliliu).

O le a fa'avasega [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) , o le fa'atulagaina o le `i18n.yml` i lenei pepa e fa'apea:

```
en:
zh: ja ko en
```

O lona uiga: Fa'aliliuga Saina i le gagana Iapani, Korea, Igilisi, fa'aliliuga Igilisi i isi gagana uma. Afai e te manaʻo e lagolagoina le gagana Saina ma le Igilisi, e mafai ona e tusi `zh: en` .

O le mea mulimuli o [le gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) , lea e maua mai ai le anotusi i le va o le ulutala autu ma le ulutala muamua o `README.md` gagana ta'itasi e fa'atupu ai se fa'amatalaga `README.md` . O le code e matua faigofie lava, e mafai ona e vaʻai i ai oe lava ia.

Google API e fa'aoga mo fa'aliliuga fua. Afai e le mafai ona e mauaina Google, fa'amolemole fetu'una'i ma seti se sui, e pei o le:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

O le fa'aliliuga fa'aliliuga o le a fa'atupuina ai se fa'aliliuga fa'aoga i `.i18n` directory, fa'amolemole siaki i `git status` ma fa'aopoopo i le fa'aputuga fa'ailoga e aloese ai mai fa'aliliuga faifaipea.

Fa'amolemole tamo'e `bunx i18n` i taimi uma e te suia ai le fa'aliliuga e fa'afou ai le cache.

Afai o le uluai tusitusiga ma le faaliliuga e suia i le taimi e tasi, o le a fenumiai le cache, o lea afai e te manaʻo e sui, e mafai ona e suia naʻo le tasi, ona tamoe lea i `bunx i18n` e faʻafouina le cache.
