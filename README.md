# Inteligência Móvel — PM

Protótipo PWA (single-file) para uso operacional — consultas rápidas e atalhos oficiais (BNMP, TJSP, validade de selo), além de utilitários de turno (lanterna, beep, notas rápidas). Dados ficam no aparelho (localStorage) — nada é enviado por padrão.

## Funcionalidades
- Campos de preenchimento rápido: Nome, CPF, RG, Placa, Nº do processo.
- Atalhos oficiais: BNMP, Validade de selo (TJSP), Consulta de processos (TJSP).
- Buscas com `site:` prontas via Google (BNMP / TJSP / combinado).
- PWA instalável, modo offline para partes estáticas, service worker básico.
- Ferramentas de turno: lanterna (torch), alarme sonoro, notas rápidas.

## Como usar
1. Copiar `index.html` para o repositório.
2. Abrir no navegador móvel e instalar como PWA (opção "Instalar" no navegador).
3. Em ambiente institucional, ajustar atalhos conforme normas.

## Privacidade e segurança
- Projeto salva dados em `localStorage` local — revisar antes de publicar.
- Remova tokens ou credenciais sensíveis antes de subir para repositório público.

## Contribuir
Abra uma issue ou PR com melhorias. Para uso institucional, valide conformidade com regulamentações internas.

## Licença
MIT (ou outra que escolher)
# intel-pm-mobile
Protótipo PWA para uso operacional — ferramenta de consultas rápidas (BNMP, TJSP, validade de selo) e utilitários de turno. Dados mantidos localmente (localStorage). Uso interno; ajustar conforme normas da corporação.
