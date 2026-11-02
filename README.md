# geoskill-cadastral-change-detection

> Topology-aware cadastral parcel change detection between two epochs. Identifies new, deleted, expanded, reduced, split, and merged parcels from cadastral vector data (宗地/地块/调查图斑). Use when comparing two epochs of land parcels, auditing boundary changes, or generating cadastral change ledgers.

See [SKILL.md](SKILL.md) for full usage, inputs and outputs.

## Quick start

```bash
python cadastral_change_detection.py --before references/sample_before.geojson --after references/sample_after.geojson --output-dir ./test
```

## License

MIT
