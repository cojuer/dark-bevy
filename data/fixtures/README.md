# Synthetic Fixtures

This directory contains original test data created specifically for
`dark-bevy`. It must not contain content extracted from the original games or
fan missions.

Each fixture should include:

- editable source data or a deterministic generator;
- a description of the behavior being tested;
- expected structural or behavioral results;
- licensing information for any third-party material.

The initial synthetic mission will eventually contain:

- one room;
- one portal connection;
- one lightmapped surface;
- one door;
- one switch;
- one AI marker;
- one objective.

Binary fixtures should remain small and should be regenerated when their source
format changes.