# Izmaiņas pēc 26.05.2025. 

- Tika atjaunināts README.md,
- Tika atjauninātas rezultātu izklājlapas - tās sākotnēji tika veidotas ar Google Sheets, bet, tās saglabājot lokāli kā Excel dokumentus, programmatūru nesaderības dēļ radās datu kļūdas. Labojumi attiecas uz formatējumu un uz aprēķinu kļūdām.

# Bakalaura darba praktiskā daļa

Latvijas Universitātes studenta Johana Justa Era bakalaura darba "Praktisks Vairākplatformu Darbvirsmas Lietojumprogrammu Izstrādes Ietvaru Salīdzinājums" praktisko eksperimentu koda repozitorija.

## Saturs

Zemāk var redzēt repozitorijas satura apkopojumu.

- `./sheets` - satur iegūto rezultātu apkopojumu, ieskaitot veiktspējas radītājiem, ABC un LOC metrikas analīzei, kā arī “Blendio” lietojumprogrammas izstrādes procesam veltīto stundu apkopojumu.
- `./devlog` - satur izstrādes žurnālu.
- `./config` - satur veiktspējas testu konfigurācijas ElectronJS un Tauri ietvariem.
- `./main.py` - galvenais koda fails veiktspējas testiem. Tam var padot šādus komandrindas parametrus:
  - `tauri_build`
  - `electronjs_build`
  - `tauri_runtime`
  - `electronjs_runtime`
  - `tauri_startup`
  - `electronjs_startup`
  - `all`
  - `all_tauri`
  - `all_electronjs`
