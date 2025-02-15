# Supported languages

The following is a list of languages for which a parser can be installed through `:TSInstall`.

Legend:
- **Tier:** _stable_, _core_, _community_, or _unsupported_
- **Queries** available for **H**ighlights, **I**ndents, **F**olds, In**J**ections, **L**ocals
- **Maintainer** of queries in nvim-treesitter (may be different from parser maintainer!)

<!--This section of the README is automatically updated by a CI job-->
<!--parserinfo-->
Language | Tier | Queries | Maintainer
-------- |:----:|:-------:| ----------
[ada](https://github.com/briot/tree-sitter-ada) | community | `HF JL` | @briot
[agda](https://github.com/tree-sitter/tree-sitter-agda) | core | `HF J ` | @Decodetalkers
[angular](https://github.com/dlvandenberg/tree-sitter-angular) | community | `HFIJL` | @dlvandenberg
[apex](https://github.com/aheber/tree-sitter-sfapex) | community | `HF JL` | @aheber, @xixiafinland
[arduino](https://github.com/tree-sitter-grammars/tree-sitter-arduino) | core | `HFIJL` | @ObserverOfTime
[asm](https://github.com/RubixDev/tree-sitter-asm) | community | `H  J ` | @RubixDev
[astro](https://github.com/virchau13/tree-sitter-astro) | community | `HFIJL` | @virchau13
[authzed](https://github.com/mleonidas/tree-sitter-authzed) | community | `H  J ` | @mattpolzin
[awk](https://github.com/Beaglefoot/tree-sitter-awk) | unsupported | `H  J ` | 
[bash](https://github.com/tree-sitter/tree-sitter-bash) | stable | `HF JL` | @TravonteD
[bass](https://github.com/vito/tree-sitter-bass) | community | `HFIJL` | @amaanq
[beancount](https://github.com/polarmutex/tree-sitter-beancount) | community | `HF J ` | @polarmutex
[bibtex](https://github.com/latex-lsp/tree-sitter-bibtex) | community | `HFIJ ` | @theHamsta, @clason
[bicep](https://github.com/tree-sitter-grammars/tree-sitter-bicep) | core | `HFIJL` | @amaanq
[bitbake](https://github.com/tree-sitter-grammars/tree-sitter-bitbake) | core | `HFIJL` | @amaanq
[blueprint](https://gitlab.com/gabmus/tree-sitter-blueprint) | unsupported | `H  J ` | @gabmus
[bp](https://github.com/ambroisie/tree-sitter-bp)[^bp] | community | `HFIJL` | @ambroisie
[c](https://github.com/tree-sitter/tree-sitter-c) | stable | `HFIJL` | @amaanq
[c_sharp](https://github.com/tree-sitter/tree-sitter-c-sharp) | core | `HF JL` | @amaanq
[cairo](https://github.com/tree-sitter-grammars/tree-sitter-cairo) | core | `HFIJL` | @amaanq
[capnp](https://github.com/tree-sitter-grammars/tree-sitter-capnp) | core | `HFIJL` | @amaanq
[chatito](https://github.com/tree-sitter-grammars/tree-sitter-chatito) | core | `HFIJL` | @ObserverOfTime
[circom](https://github.com/Decurity/tree-sitter-circom) | community | `HF JL` | @alexandr-martirosyan
[clojure](https://github.com/sogaiu/tree-sitter-clojure) | community | `HF JL` | @NoahTheDuke
[cmake](https://github.com/uyha/tree-sitter-cmake) | community | `HFIJ ` | @uyha
[comment](https://github.com/stsewd/tree-sitter-comment) | community | `H    ` | @stsewd
[commonlisp](https://github.com/tree-sitter-grammars/tree-sitter-commonlisp) | core | `HF JL` | @theHamsta
[cooklang](https://github.com/addcninblue/tree-sitter-cooklang) | community | `H  J ` | @addcninblue
[corn](https://github.com/jakestanger/tree-sitter-corn) | community | `HFIJL` | @jakestanger
[cpon](https://github.com/tree-sitter-grammars/tree-sitter-cpon) | core | `HFIJL` | @amaanq
[cpp](https://github.com/tree-sitter/tree-sitter-cpp) | core | `HFIJL` | @theHamsta
[css](https://github.com/tree-sitter/tree-sitter-css) | core | `HFIJ ` | @TravonteD
[csv](https://github.com/tree-sitter-grammars/tree-sitter-csv) | core | `H    ` | @amaanq
[cuda](https://github.com/tree-sitter-grammars/tree-sitter-cuda) | core | `HFIJL` | @theHamsta
[cue](https://github.com/eonpatapon/tree-sitter-cue) | community | `HFIJL` | @amaanq
[cylc](https://github.com/elliotfontaine/tree-sitter-cylc) | community | `HFIJ ` | @elliotfontaine
[d](https://github.com/gdamore/tree-sitter-d) | community | `HFIJL` | @amaanq
[dart](https://github.com/UserNobody14/tree-sitter-dart) | community | `HFIJL` | @akinsho
[desktop](https://github.com/ValdezFOmar/tree-sitter-desktop) | community | `HF J ` | @ValdezFOmar
[devicetree](https://github.com/joelspadin/tree-sitter-devicetree) | community | `HFIJL` | @jedrzejboczar
[dhall](https://github.com/jbellerb/tree-sitter-dhall) | community | `HF J ` | @amaanq
[diff](https://github.com/the-mikedavis/tree-sitter-diff) | community | `HF J ` | @gbprod
[disassembly](https://github.com/ColinKennedy/tree-sitter-disassembly) | community | `H  J ` | @ColinKennedy
[djot](https://github.com/treeman/tree-sitter-djot) | community | `HFIJL` | @NoahTheDuke
[dockerfile](https://github.com/camdencheek/tree-sitter-dockerfile) | community | `H  J ` | @camdencheek
[dot](https://github.com/rydesun/tree-sitter-dot) | community | `H IJ ` | @rydesun
[doxygen](https://github.com/tree-sitter-grammars/tree-sitter-doxygen) | core | `H IJ ` | @amaanq
[dtd](https://github.com/tree-sitter-grammars/tree-sitter-xml) | core | `HF JL` | @ObserverOfTime
[earthfile](https://github.com/glehmann/tree-sitter-earthfile) | community | `H  J ` | @glehmann
[ebnf](https://github.com/RubixDev/ebnf) | community | `H  J ` | @RubixDev
ecma (queries only)[^ecma] | community | `HFIJL` | @steelsojka
[editorconfig](https://github.com/ValdezFOmar/tree-sitter-editorconfig) | community | `HF J ` | @ValdezFOmar
[eds](https://github.com/uyha/tree-sitter-eds) | community | `HF   ` | @uyha
[eex](https://github.com/connorlay/tree-sitter-eex) | community | `H  J ` | @connorlay
[elixir](https://github.com/elixir-lang/tree-sitter-elixir) | community | `HFIJL` | @connorlay
[elm](https://github.com/elm-tooling/tree-sitter-elm) | community | `HF J ` | @zweimach
[elsa](https://github.com/glapa-grossklag/tree-sitter-elsa) | community | `HFIJL` | @glapa-grossklag, @amaanq
[elvish](https://github.com/elves/tree-sitter-elvish) | community | `H  J ` | @elves
[embedded_template](https://github.com/tree-sitter/tree-sitter-embedded-template) | unsupported | `H  J ` | 
[erlang](https://github.com/WhatsApp/tree-sitter-erlang) | community | `HF J ` | @filmor
[facility](https://github.com/FacilityApi/tree-sitter-facility) | community | `HFIJ ` | @bryankenote
[faust](https://github.com/khiner/tree-sitter-faust) | community | `H  J ` | @khiner
[fennel](https://github.com/alexmozaidze/tree-sitter-fennel) | community | `HF JL` | @alexmozaidze
[fidl](https://github.com/google/tree-sitter-fidl) | community | `HF J ` | @chaopeng
[firrtl](https://github.com/tree-sitter-grammars/tree-sitter-firrtl) | core | `HFIJL` | @amaanq
[fish](https://github.com/ram02z/tree-sitter-fish) | community | `HFIJL` | @ram02z
[foam](https://github.com/FoamScience/tree-sitter-foam) | community | `HFIJL` | @FoamScience
[forth](https://github.com/AlexanderBrevig/tree-sitter-forth) | community | `HFIJL` | @amaanq
[fortran](https://github.com/stadelmanma/tree-sitter-fortran) | community | `HFIJ ` | @amaanq
[fsh](https://github.com/mgramigna/tree-sitter-fsh) | community | `H  J ` | @mgramigna
[fsharp](https://github.com/ionide/tree-sitter-fsharp) | community | `H  J ` | @nsidorenco
[func](https://github.com/tree-sitter-grammars/tree-sitter-func) | core | `H  J ` | @amaanq
[fusion](https://gitlab.com/jirgn/tree-sitter-fusion) | community | `HFIJL` | @jirgn
[gap](https://github.com/gap-system/tree-sitter-gap)[^gap] | community | `HF JL` | @reiniscirpons
[gaptst](https://github.com/gap-system/tree-sitter-gaptst)[^gaptst] | community | `HF J ` | @reiniscirpons
[gdscript](https://github.com/PrestonKnopp/tree-sitter-gdscript)[^gdscript] | community | `HFIJL` | @PrestonKnopp
[gdshader](https://github.com/GodOfAvacyn/tree-sitter-gdshader) | community | `H  J ` | @godofavacyn
[git_config](https://github.com/the-mikedavis/tree-sitter-git-config) | community | `HF J ` | @amaanq
[git_rebase](https://github.com/the-mikedavis/tree-sitter-git-rebase) | community | `H  J ` | @gbprod
[gitattributes](https://github.com/tree-sitter-grammars/tree-sitter-gitattributes) | core | `H  JL` | @ObserverOfTime
[gitcommit](https://github.com/gbprod/tree-sitter-gitcommit) | community | `H  J ` | @gbprod
[gitignore](https://github.com/shunsambongi/tree-sitter-gitignore) | community | `H  J ` | @theHamsta
[gleam](https://github.com/gleam-lang/tree-sitter-gleam) | community | `HFIJL` | @amaanq
[glimmer](https://github.com/ember-tooling/tree-sitter-glimmer)[^glimmer] | community | `HFIJL` | @NullVoxPopuli
[glimmer_javascript](https://github.com/NullVoxPopuli/tree-sitter-glimmer-javascript) | community | `H IJL` | @NullVoxPopuli
[glimmer_typescript](https://github.com/NullVoxPopuli/tree-sitter-glimmer-typescript) | community | `H IJ ` | @NullVoxPopuli
[glsl](https://github.com/tree-sitter-grammars/tree-sitter-glsl) | core | `HFIJL` | @theHamsta
[gn](https://github.com/tree-sitter-grammars/tree-sitter-gn) | core | `HFIJL` | @amaanq
[gnuplot](https://github.com/dpezto/tree-sitter-gnuplot) | community | `H  J ` | @dpezto
[go](https://github.com/tree-sitter/tree-sitter-go) | core | `HFIJL` | @theHamsta, @WinWisely268
[goctl](https://github.com/chaozwn/tree-sitter-goctl) | community | `HFIJ ` | @chaozwn
[godot_resource](https://github.com/PrestonKnopp/tree-sitter-godot-resource)[^godot_resource] | community | `HF JL` | @pierpo
[gomod](https://github.com/camdencheek/tree-sitter-go-mod) | community | `H  J ` | @camdencheek
[gosum](https://github.com/tree-sitter-grammars/tree-sitter-go-sum) | core | `H    ` | @amaanq
[gotmpl](https://github.com/ngalaiko/tree-sitter-go-template) | community | `HF JL` | @qvalentin
[gowork](https://github.com/omertuc/tree-sitter-go-work) | community | `H  J ` | @omertuc
[gpg](https://github.com/tree-sitter-grammars/tree-sitter-gpg-config) | core | `H  J ` | @ObserverOfTime
[graphql](https://github.com/bkegley/tree-sitter-graphql) | community | `H IJ ` | @bkegley
[gren](https://github.com/MaeBrooks/tree-sitter-gren) | community | `H  J ` | @MaeBrooks
[groovy](https://github.com/murtaza64/tree-sitter-groovy) | community | `HFIJL` | @murtaza64
[gstlaunch](https://github.com/tree-sitter-grammars/tree-sitter-gstlaunch) | core | `H    ` | @theHamsta
[hack](https://github.com/slackhq/tree-sitter-hack) | unsupported | `H  J ` | 
[hare](https://github.com/tree-sitter-grammars/tree-sitter-hare) | core | `HFIJL` | @amaanq
[haskell](https://github.com/tree-sitter/tree-sitter-haskell) | core | `HF JL` | @mrcjkb
[haskell_persistent](https://github.com/MercuryTechnologies/tree-sitter-haskell-persistent) | community | `HF   ` | @lykahb
[hcl](https://github.com/tree-sitter-grammars/tree-sitter-hcl) | core | `HFIJ ` | @MichaHoffmann
[heex](https://github.com/connorlay/tree-sitter-heex) | community | `HFIJL` | @connorlay
[helm](https://github.com/ngalaiko/tree-sitter-go-template) | community | `HF JL` | @qvalentin
[hjson](https://github.com/winston0410/tree-sitter-hjson) | community | `HFIJL` | @winston0410
[hlsl](https://github.com/tree-sitter-grammars/tree-sitter-hlsl) | core | `HFIJL` | @theHamsta
[hlsplaylist](https://github.com/Freed-Wu/tree-sitter-hlsplaylist) | community | `H  J ` | @Freed-Wu
[hocon](https://github.com/antosha417/tree-sitter-hocon) | unsupported | `HF J ` | @antosha417
[hoon](https://github.com/urbit-pilled/tree-sitter-hoon) | community | `HF JL` | @urbit-pilled
[html](https://github.com/tree-sitter/tree-sitter-html) | core | `HFIJL` | @TravonteD
html_tags (queries only)[^html_tags] | community | `H IJ ` | @TravonteD
[htmldjango](https://github.com/interdependence/tree-sitter-htmldjango) | community | `HFIJ ` | @ObserverOfTime
[http](https://github.com/rest-nvim/tree-sitter-http) | community | `H  J ` | @amaanq, @NTBBloodbath
[hurl](https://github.com/pfeiferj/tree-sitter-hurl) | community | `HFIJ ` | @pfeiferj
[hyprlang](https://github.com/tree-sitter-grammars/tree-sitter-hyprlang) | core | `HFIJ ` | @luckasRanarison
[idl](https://github.com/cathaysia/tree-sitter-idl) | community | `H IJ ` | @cathaysia
[ini](https://github.com/justinmk/tree-sitter-ini) | community | `HF J ` | @theHamsta
[inko](https://github.com/inko-lang/tree-sitter-inko) | community | `HFIJL` | @yorickpeterse
[ipkg](https://github.com/srghma/tree-sitter-ipkg) | community | `HFIJL` | @srghma
[ispc](https://github.com/tree-sitter-grammars/tree-sitter-ispc) | core | `HFIJL` | @fab4100
[janet_simple](https://github.com/sogaiu/tree-sitter-janet-simple) | community | `HF JL` | @sogaiu
[java](https://github.com/tree-sitter/tree-sitter-java) | core | `HFIJL` | @p00f
[javascript](https://github.com/tree-sitter/tree-sitter-javascript) | core | `HFIJL` | @steelsojka
[jq](https://github.com/flurie/tree-sitter-jq) | community | `H  JL` | @ObserverOfTime
[jsdoc](https://github.com/tree-sitter/tree-sitter-jsdoc) | core | `H    ` | @steelsojka
[json](https://github.com/tree-sitter/tree-sitter-json) | core | `HFI L` | @steelsojka
[json5](https://github.com/Joakker/tree-sitter-json5) | community | `H  J ` | @Joakker
[jsonc](https://gitlab.com/WhyNotHugo/tree-sitter-jsonc) | community | `HFIJL` | @WhyNotHugo
[jsonnet](https://github.com/sourcegraph/tree-sitter-jsonnet) | community | `HF JL` | @nawordar
jsx (queries only)[^jsx] | community | `HFIJ ` | @steelsojka
[julia](https://github.com/tree-sitter/tree-sitter-julia) | community | `HFIJL` | @fredrikekre
[just](https://github.com/IndianBoy42/tree-sitter-just) | community | `HFIJL` | @Hubro
[kconfig](https://github.com/tree-sitter-grammars/tree-sitter-kconfig) | core | `HFIJL` | @amaanq
[kdl](https://github.com/tree-sitter-grammars/tree-sitter-kdl) | core | `HFIJL` | @amaanq
[kotlin](https://github.com/fwcd/tree-sitter-kotlin) | community | `HF JL` | @SalBakraa
[koto](https://github.com/koto-lang/tree-sitter-koto) | community | `HF JL` | @irh
[kusto](https://github.com/Willem-J-an/tree-sitter-kusto) | community | `H  J ` | @Willem-J-an
[lalrpop](https://github.com/traxys/tree-sitter-lalrpop) | community | `HF JL` | @traxys
[latex](https://github.com/latex-lsp/tree-sitter-latex) | community | `HF J ` | @theHamsta, @clason
[ledger](https://github.com/cbarrete/tree-sitter-ledger) | community | `HFIJ ` | @cbarrete
[leo](https://github.com/r001/tree-sitter-leo) | community | `H IJ ` | @r001
[linkerscript](https://github.com/tree-sitter-grammars/tree-sitter-linkerscript) | core | `HFIJL` | @amaanq
[liquid](https://github.com/hankthetank27/tree-sitter-liquid) | community | `H  J ` | @hankthetank27
[liquidsoap](https://github.com/savonet/tree-sitter-liquidsoap) | community | `HFIJL` | @toots
[llvm](https://github.com/benwilliamgraham/tree-sitter-llvm) | community | `H  J ` | @benwilliamgraham
[lua](https://github.com/tree-sitter-grammars/tree-sitter-lua) | stable | `HFIJL` | @muniftanjim
[luadoc](https://github.com/tree-sitter-grammars/tree-sitter-luadoc) | core | `H    ` | @amaanq
[luap](https://github.com/tree-sitter-grammars/tree-sitter-luap)[^luap] | core | `H    ` | @amaanq
[luau](https://github.com/tree-sitter-grammars/tree-sitter-luau) | core | `HFIJL` | @amaanq
[m68k](https://github.com/grahambates/tree-sitter-m68k) | community | `HF JL` | @grahambates
[make](https://github.com/alemuller/tree-sitter-make) | community | `HF J ` | @lewis6991
[markdown](https://github.com/tree-sitter-grammars/tree-sitter-markdown)[^markdown] | stable | `HFIJ ` | @MDeiml
[markdown_inline](https://github.com/tree-sitter-grammars/tree-sitter-markdown)[^markdown_inline] | stable | `H  J ` | @MDeiml
[matlab](https://github.com/acristoffers/tree-sitter-matlab) | community | `HFIJL` | @acristoffers
[menhir](https://github.com/Kerl13/tree-sitter-menhir) | community | `H  J ` | @Kerl13
[mermaid](https://github.com/monaqa/tree-sitter-mermaid) | unsupported | `HFIJ ` | 
[meson](https://github.com/tree-sitter-grammars/tree-sitter-meson) | core | `HFIJ ` | @Decodetalkers
[mlir](https://github.com/artagnon/tree-sitter-mlir) | community | `H  JL` | @artagnon
[muttrc](https://github.com/neomutt/tree-sitter-muttrc) | community | `H  J ` | @Freed-Wu
[nasm](https://github.com/naclsn/tree-sitter-nasm) | community | `H  J ` | @ObserverOfTime
[nginx](https://github.com/opa-oz/tree-sitter-nginx) | community | `HF J ` | @opa-oz
[nickel](https://github.com/nickel-lang/tree-sitter-nickel) | unsupported | `H IJ ` | 
[nim](https://github.com/alaviss/tree-sitter-nim) | community | `HF JL` | @aMOPel
[nim_format_string](https://github.com/aMOPel/tree-sitter-nim-format-string) | community | `H  J ` | @aMOPel
[ninja](https://github.com/alemuller/tree-sitter-ninja) | community | `HFIJ ` | @alemuller
[nix](https://github.com/cstrahan/tree-sitter-nix) | community | `HFIJL` | @leo60228
[nqc](https://github.com/tree-sitter-grammars/tree-sitter-nqc) | core | `HFIJL` | @amaanq
[nu](https://github.com/nushell/tree-sitter-nu) | community | `H IJ ` | @abhisheksingh0x558
[objc](https://github.com/tree-sitter-grammars/tree-sitter-objc) | core | `HFIJL` | @amaanq
[objdump](https://github.com/ColinKennedy/tree-sitter-objdump) | community | `H  J ` | @ColinKennedy
[ocaml](https://github.com/tree-sitter/tree-sitter-ocaml) | core | `HFIJL` | @undu
[ocaml_interface](https://github.com/tree-sitter/tree-sitter-ocaml) | core | `HFIJL` | @undu
[ocamllex](https://github.com/atom-ocaml/tree-sitter-ocamllex) | community | `H  J ` | @undu
[odin](https://github.com/tree-sitter-grammars/tree-sitter-odin) | core | `HFIJL` | @amaanq
[org](https://github.com/milisims/tree-sitter-org) | unsupported | `     ` | 
[pascal](https://github.com/Isopod/tree-sitter-pascal) | community | `HFIJL` | @Isopod
[passwd](https://github.com/ath3/tree-sitter-passwd) | community | `H    ` | @amaanq
[pem](https://github.com/tree-sitter-grammars/tree-sitter-pem) | core | `HF J ` | @ObserverOfTime
[perl](https://github.com/tree-sitter-perl/tree-sitter-perl) | community | `HF J ` | @RabbiVeesh, @LeoNerd
[php](https://github.com/tree-sitter/tree-sitter-php)[^php] | core | `HFIJL` | @tk-shirasaka, @calebdw
[php_only](https://github.com/tree-sitter/tree-sitter-php)[^php_only] | core | `HFIJL` | @tk-shirasaka, @calebdw
[phpdoc](https://github.com/claytonrcarter/tree-sitter-phpdoc) | community | `H    ` | @mikehaertl
[pioasm](https://github.com/leo60228/tree-sitter-pioasm) | community | `H  J ` | @leo60228
[po](https://github.com/tree-sitter-grammars/tree-sitter-po) | core | `HF J ` | @amaanq
[pod](https://github.com/tree-sitter-perl/tree-sitter-pod) | community | `H    ` | @RabbiVeesh, @LeoNerd
[poe_filter](https://github.com/tree-sitter-grammars/tree-sitter-poe-filter)[^poe_filter] | core | `HFIJ ` | @ObserverOfTime
[pony](https://github.com/tree-sitter-grammars/tree-sitter-pony) | core | `HFIJL` | @amaanq, @mfelsche
[powershell](https://github.com/airbus-cert/tree-sitter-powershell) | community | `HFIJL` | @L2jLiga
[printf](https://github.com/tree-sitter-grammars/tree-sitter-printf) | core | `H    ` | @ObserverOfTime
[prisma](https://github.com/victorhqc/tree-sitter-prisma) | community | `HF J ` | @elianiva
[problog](https://github.com/foxyseta/tree-sitter-prolog) | community | `HFIJ ` | @foxyseta
[prolog](https://github.com/foxyseta/tree-sitter-prolog) | community | `HFIJ ` | @foxyseta
[promql](https://github.com/MichaHoffmann/tree-sitter-promql) | community | `H  J ` | @MichaHoffmann
[properties](https://github.com/tree-sitter-grammars/tree-sitter-properties)[^properties] | core | `H  JL` | @ObserverOfTime
[proto](https://github.com/treywood/tree-sitter-proto) | community | `HFIJ ` | @treywood
[prql](https://github.com/PRQL/tree-sitter-prql) | community | `H  J ` | @matthias-Q
[psv](https://github.com/tree-sitter-grammars/tree-sitter-csv) | core | `H    ` | @amaanq
[pug](https://github.com/zealot128/tree-sitter-pug) | community | `H  J ` | @zealot128
[puppet](https://github.com/tree-sitter-grammars/tree-sitter-puppet) | core | `HFIJL` | @amaanq
[purescript](https://github.com/postsolar/tree-sitter-purescript) | community | `H  JL` | @postsolar
[pymanifest](https://github.com/tree-sitter-grammars/tree-sitter-pymanifest) | core | `H  J ` | @ObserverOfTime
[python](https://github.com/tree-sitter/tree-sitter-python) | stable | `HFIJL` | @stsewd, @theHamsta
[ql](https://github.com/tree-sitter/tree-sitter-ql) | core | `HFIJL` | @pwntester
[qmldir](https://github.com/tree-sitter-grammars/tree-sitter-qmldir) | core | `H  J ` | @amaanq
[qmljs](https://github.com/yuja/tree-sitter-qmljs) | community | `HF J ` | @Decodetalkers
[query](https://github.com/tree-sitter-grammars/tree-sitter-query)[^query] | stable | `HFIJL` | @steelsojka
[r](https://github.com/r-lib/tree-sitter-r) | community | `H IJL` | @ribru17
[racket](https://github.com/6cdh/tree-sitter-racket) | unsupported | `HF J ` | 
[ralph](https://github.com/alephium/tree-sitter-ralph) | community | `H  J ` | @tdroxler
[rasi](https://github.com/Fymyte/tree-sitter-rasi) | community | `HFIJL` | @Fymyte
[rbs](https://github.com/joker1007/tree-sitter-rbs) | community | `HFIJ ` | @joker1007
[re2c](https://github.com/tree-sitter-grammars/tree-sitter-re2c) | core | `HFIJL` | @amaanq
[readline](https://github.com/tree-sitter-grammars/tree-sitter-readline) | core | `HFIJ ` | @ribru17
[regex](https://github.com/tree-sitter/tree-sitter-regex) | core | `H    ` | @theHamsta
[rego](https://github.com/FallenAngel97/tree-sitter-rego) | community | `H  J ` | @FallenAngel97
[requirements](https://github.com/tree-sitter-grammars/tree-sitter-requirements) | core | `H  J ` | @ObserverOfTime
[rescript](https://github.com/rescript-lang/tree-sitter-rescript) | core | `HFIJL` | @ribru17
[rnoweb](https://github.com/bamonroe/tree-sitter-rnoweb) | community | `HF J ` | @bamonroe
[robot](https://github.com/Hubro/tree-sitter-robot) | community | `HFIJ ` | @Hubro
[robots](https://github.com/opa-oz/tree-sitter-robots-txt) | community | `H  J ` | @opa-oz
[roc](https://github.com/faldor20/tree-sitter-roc) | community | `H  JL` | @nat-418
[ron](https://github.com/tree-sitter-grammars/tree-sitter-ron) | core | `HFIJL` | @amaanq
[rst](https://github.com/stsewd/tree-sitter-rst) | community | `H  JL` | @stsewd
[ruby](https://github.com/tree-sitter/tree-sitter-ruby) | core | `HFIJL` | @TravonteD
[runescript](https://github.com/2004Scape/tree-sitter-runescript) | community | `H  J ` | @2004Scape
[rust](https://github.com/tree-sitter/tree-sitter-rust) | core | `HFIJL` | @amaanq
[scala](https://github.com/tree-sitter/tree-sitter-scala) | core | `HF JL` | @stevanmilic
[scfg](https://github.com/rockorager/tree-sitter-scfg) | unsupported | `H  J ` | @WhyNotHugo
[scheme](https://github.com/6cdh/tree-sitter-scheme) | unsupported | `HF J ` | 
[scss](https://github.com/serenadeai/tree-sitter-scss) | community | `HFIJ ` | @elianiva
[sflog](https://github.com/aheber/tree-sitter-sfapex)[^sflog] | community | `H    ` | @aheber, @xixiaofinland
[slang](https://github.com/tree-sitter-grammars/tree-sitter-slang)[^slang] | core | `HFIJL` | @theHamsta
[slint](https://github.com/slint-ui/tree-sitter-slint) | community | `HFIJL` | @hunger
[smali](https://github.com/tree-sitter-grammars/tree-sitter-smali) | core | `HFIJL` | @amaanq
[smithy](https://github.com/indoorvivants/tree-sitter-smithy) | community | `H  J ` | @amaanq, @keynmol
[snakemake](https://github.com/osthomas/tree-sitter-snakemake) | community | `HFIJL` | @osthomas
[solidity](https://github.com/JoranHonig/tree-sitter-solidity) | community | `HF J ` | @amaanq
[soql](https://github.com/aheber/tree-sitter-sfapex) | community | `H    ` | @aheber, @xixiafinland
[sosl](https://github.com/aheber/tree-sitter-sfapex) | community | `H    ` | @aheber, @xixiafinland
[sourcepawn](https://github.com/nilshelmig/tree-sitter-sourcepawn) | community | `H  JL` | @Sarrus1
[sparql](https://github.com/GordianDziwis/tree-sitter-sparql) | community | `HFIJL` | @GordianDziwis
[sql](https://github.com/derekstride/tree-sitter-sql) | community | `H IJ ` | @derekstride
[squirrel](https://github.com/tree-sitter-grammars/tree-sitter-squirrel) | core | `HFIJL` | @amaanq
[ssh_config](https://github.com/tree-sitter-grammars/tree-sitter-ssh-config) | core | `HFIJL` | @ObserverOfTime
[starlark](https://github.com/tree-sitter-grammars/tree-sitter-starlark) | core | `HFIJL` | @amaanq
[strace](https://github.com/sigmaSd/tree-sitter-strace) | community | `H  J ` | @amaanq
[styled](https://github.com/mskelton/tree-sitter-styled) | community | `HFIJ ` | @mskelton
[supercollider](https://github.com/madskjeldgaard/tree-sitter-supercollider) | community | `HFIJL` | @madskjeldgaard
[superhtml](https://github.com/kristoff-it/superhtml) | community | `H  J ` | @rockorager
[surface](https://github.com/connorlay/tree-sitter-surface) | community | `HFIJ ` | @connorlay
[svelte](https://github.com/tree-sitter-grammars/tree-sitter-svelte) | core | `HFIJL` | @amaanq
[sway](https://github.com/FuelLabs/tree-sitter-sway.git) | core | `HFIJL` | @ribru17
[swift](https://github.com/alex-pinkus/tree-sitter-swift) | community | `HFIJL` | @alex-pinkus
[sxhkdrc](https://github.com/RaafatTurki/tree-sitter-sxhkdrc) | community | `HF J ` | @RaafatTurki
[systemtap](https://github.com/ok-ryoko/tree-sitter-systemtap) | community | `HF JL` | @ok-ryoko
[t32](https://gitlab.com/xasc/tree-sitter-t32) | community | `HFIJL` | @xasc
[tablegen](https://github.com/tree-sitter-grammars/tree-sitter-tablegen) | core | `HFIJL` | @amaanq
[tact](https://github.com/tact-lang/tree-sitter-tact) | community | `HFIJL` | @novusnota
[tcl](https://github.com/tree-sitter-grammars/tree-sitter-tcl) | core | `HFIJ ` | @lewis6991
[teal](https://github.com/euclidianAce/tree-sitter-teal) | community | `HFIJL` | @euclidianAce
[templ](https://github.com/vrischmann/tree-sitter-templ) | community | `HF J ` | @vrischmann
[terraform](https://github.com/MichaHoffmann/tree-sitter-hcl) | community | `HFIJ ` | @MichaHoffmann
[textproto](https://github.com/PorterAtGoogle/tree-sitter-textproto) | community | `HFIJ ` | @Porter
[thrift](https://github.com/tree-sitter-grammars/tree-sitter-thrift) | core | `HFIJL` | @amaanq, @duskmoon314
[tiger](https://github.com/ambroisie/tree-sitter-tiger) | community | `HFIJL` | @ambroisie
[tlaplus](https://github.com/tlaplus-community/tree-sitter-tlaplus) | community | `HF JL` | @ahelwer, @susliko
[tmux](https://github.com/Freed-Wu/tree-sitter-tmux) | community | `H  J ` | @Freed-Wu
[todotxt](https://github.com/arnarg/tree-sitter-todotxt) | community | `H    ` | @arnarg
[toml](https://github.com/tree-sitter-grammars/tree-sitter-toml) | core | `HFIJL` | @tk-shirasaka
[tsv](https://github.com/tree-sitter-grammars/tree-sitter-csv) | core | `H    ` | @amaanq
[tsx](https://github.com/tree-sitter/tree-sitter-typescript) | core | `HFIJL` | @steelsojka
[turtle](https://github.com/GordianDziwis/tree-sitter-turtle) | community | `HFIJL` | @GordianDziwis
[twig](https://github.com/gbprod/tree-sitter-twig) | community | `H  J ` | @gbprod
[typescript](https://github.com/tree-sitter/tree-sitter-typescript) | core | `HFIJL` | @steelsojka
[typespec](https://github.com/happenslol/tree-sitter-typespec) | community | `H IJ ` | @happenslol
[typoscript](https://github.com/Teddytrombone/tree-sitter-typoscript) | community | `HFIJ ` | @Teddytrombone
[typst](https://github.com/uben0/tree-sitter-typst) | community | `HFIJ ` | @uben0, @RaafatTurki
[udev](https://github.com/tree-sitter-grammars/tree-sitter-udev) | core | `H  JL` | @ObserverOfTime
[ungrammar](https://github.com/tree-sitter-grammars/tree-sitter-ungrammar) | core | `HFIJL` | @Philipp-M, @amaanq
[unison](https://github.com/kylegoetz/tree-sitter-unison) | community | `HF J ` | @tapegram
[usd](https://github.com/ColinKennedy/tree-sitter-usd) | community | `HFIJL` | @ColinKennedy
[uxntal](https://github.com/tree-sitter-grammars/tree-sitter-uxntal) | core | `HFIJL` | @amaanq
[v](https://github.com/vlang/v-analyzer) | community | `HFIJL` | @kkharji, @amaanq
[vala](https://github.com/vala-lang/tree-sitter-vala) | community | `HF J ` | @Prince781
[vento](https://github.com/ventojs/tree-sitter-vento) | community | `H  J ` | @wrapperup, @oscarotero
[verilog](https://github.com/gmlarumbe/tree-sitter-systemverilog) | community | `HF J ` | @zhangwwpeng
[vhdl](https://github.com/jpt13653903/tree-sitter-vhdl) | community | `HF J ` | @jpt13653903
[vhs](https://github.com/charmbracelet/tree-sitter-vhs) | community | `H  J ` | @caarlos0
[vim](https://github.com/tree-sitter-grammars/tree-sitter-vim) | stable | `HF JL` | @clason
[vimdoc](https://github.com/neovim/tree-sitter-vimdoc) | stable | `H  J ` | @clason
[vrl](https://github.com/belltoy/tree-sitter-vrl) | community | `HFIJL` | @belltoy
[vue](https://github.com/tree-sitter-grammars/tree-sitter-vue) | core | `HFIJ ` | @WhyNotHugo, @lucario387
[wgsl](https://github.com/szebniok/tree-sitter-wgsl) | community | `HFIJ ` | @szebniok
[wgsl_bevy](https://github.com/tree-sitter-grammars/tree-sitter-wgsl-bevy) | core | `HFI  ` | @theHamsta
[wing](https://github.com/winglang/tree-sitter-wing) | community | `HF JL` | @gshpychka, @MarkMcCulloh
[wit](https://github.com/liamwh/tree-sitter-wit) | community | `HF J ` | @liamwh
[xcompose](https://github.com/tree-sitter-grammars/tree-sitter-xcompose) | core | `H  JL` | @ObserverOfTime
[xml](https://github.com/tree-sitter-grammars/tree-sitter-xml) | core | `HFIJL` | @ObserverOfTime
[xresources](https://github.com/ValdezFOmar/tree-sitter-xresources) | community | `HF JL` | @ValdezFOmar
[yaml](https://github.com/tree-sitter-grammars/tree-sitter-yaml) | core | `HFIJL` | @amaanq
[yang](https://github.com/Hubro/tree-sitter-yang) | community | `HFIJ ` | @Hubro
[yuck](https://github.com/tree-sitter-grammars/tree-sitter-yuck) | core | `HFIJL` | @Philipp-M, @amaanq
[zathurarc](https://github.com/Freed-Wu/tree-sitter-zathurarc) | community | `H  J ` | @Freed-Wu
[zig](https://github.com/tree-sitter-grammars/tree-sitter-zig) | stable | `HFIJL` | @amaanq
[ziggy](https://github.com/kristoff-it/ziggy) | community | `H I  ` | @rockorager
[ziggy_schema](https://github.com/kristoff-it/ziggy) | community | `H I  ` | @rockorager
[^bp]: Android Blueprint
[^ecma]: queries required by javascript, typescript, tsx, qmljs
[^gap]: GAP system
[^gaptst]: GAP system test files
[^gdscript]: Godot
[^glimmer]: Glimmer and Ember
[^godot_resource]: Godot Resources
[^html_tags]: queries required by html, astro, vue, svelte
[^jsx]: queries required by javascript, tsx
[^luap]: Lua patterns
[^markdown]: basic highlighting
[^markdown_inline]: needed for full highlighting
[^php]: PHP with embedded HTML
[^php_only]: PHP without embedded HTML
[^poe_filter]: Path of Exile item filter
[^properties]: Java properties files
[^query]: Tree-sitter query language
[^sflog]: Salesforce debug log
[^slang]: Shader Slang
<!--parserinfo-->
