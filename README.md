# actor-isekai — Isekai world-state and gameplay-event actor

`actor-isekai` owns the governed world-state, crafting, creature-roster, and
gameplay-event boundary for the Isekai experience. Its canonical repository is
`network-awai/actor-isekai`.

The neighboring `network-awai/network-isekai` repository owns the public
isekai.network application, browser renderer, editor, fork/publish flow, and
asset hub. This actor owns only event/world-state orchestration and compatibility
collections; it does not duplicate the application runtime. Historical
etzhayyim DID, namespace, Radicle identity, and GitHub URL remain aliases.

Run `clojure -M:test` for the executable contract suite.
