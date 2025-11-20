# channel_yield
Maximizing Channel Yield in Digital Transaction

What this demo does

Ingests session/page-view logs (user/session, timestamp, page)

Builds a period graph (directed) of page → next_page transitions for a measurement period

Computes edge transition counts, node-level reach / conversion and edge leakage metrics

Creates a temporal reference (baseline graph) and updates the current period graph with exponential smoothing so changes are visible yet stable

Identifies and ranks links (edges) with high yield leakage and shows where they lead

Includes a synthetic example and simple plotting helpers for quick evaluation

Dependencies: pandas, networkx, numpy, matplotlib (all pip installable)
