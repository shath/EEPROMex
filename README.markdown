# Modified Arduino EEPROMex library 

Original EEPROMex library can be found here

[http://thijs.elenbaas.net/downloads/?did=3](http://thijs.elenbaas.net/downloads/?did=3)

This is a slight modification to original with possibility to store uint64_t type
values.

### Modifications

Two new functions

```
uint64_t readLongLong(int address);
bool writeLongLong(int address, uint64_t value);
```

Not implemented yet

```
bool updateLongLong(int address, uint64_t value);
```

The rest should be exactly like EEPROMex as of March 9th 2014.