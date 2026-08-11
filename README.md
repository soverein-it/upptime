# RIN driftsstatus

[![Uptime CI](https://github.com/soverein-it/upptime/workflows/Uptime%20CI/badge.svg)](https://github.com/soverein-it/upptime/actions?query=workflow%3A%22Uptime+CI%22)

Ekstern overvåkning av tjenestene til [RIN AS](https://rin.no), drevet av
[Upptime](https://upptime.js.org). Endepunktene sjekkes hvert femte minutt
fra GitHub Actions — utenfra, slik kundene når dem. Statussiden ligger på
[status.rin.no](https://status.rin.no).

Ved nedetid åpnes automatisk en issue i dette repoet, og den lukkes når
tjenesten er tilbake. Oppetidshistorikk og responstider ligger i
[`history/`](./history) og [`graphs/`](./graphs).

## Live status

<!--start: status pages-->
<!--end: status pages-->

## Drift

For internt driftsapparat (in-fleet-metrikker, alarmer, runbooks): se
rin-repoet — `infra/` og `docs/downtime/`. Dette er den eksterne vinkelen.

Listen over endepunkter vedlikeholdes i [`.upptimerc.yml`](./.upptimerc.yml).
