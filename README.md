# 11ty static page example

Ukázkový repozitář jednoduchého statického webu generovaného pomocí Eleventy a nasazovaného automaticky na Github pages pomocí Github actions.

## Github Actions 

Github actions umožňují automatizovat procesy v rámci Github repozitářů.
V případě tohoto repozitáře jde o automatický build webu pomocí `npx @11ty/eleventy` a následné nahrání buildu ve složce `_site` do Github pages.
Výhodou tohoto řešení je, že nemusíme build dělat manuálně, pří pushi do main branch se web automaticky zbuildí a deployne.

