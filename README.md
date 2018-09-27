# EDID-Parser-Windows
Fetches and print to console the EDID block for all monitors.

## Example:

```
Found monitor:
  name: [\\.\DISPLAY2]
  device name: [MONITOR\LEN40A9\{4d36e96e-e325-11ce-bfc1-08002be10318}\0002]
  device str: [Generic PnP Monitor]
  status: Primary
  is-active: true
  rect (LTRB): 0 0 1536 864
  work (LTRB): 0 0 1536 864
  physical width x height: 309mm  x  173mm
Found monitor:
  name: [\\.\DISPLAY1]
  device name: [MONITOR\HWP2690\{4d36e96e-e325-11ce-bfc1-08002be10318}\0006]
  device str: [Generic PnP Monitor]
  status: Not-primary
  is-active: true
  rect (LTRB): 1920 -926 4480 674
  work (LTRB): 1920 -926 4480 674
  physical width x height: 641mm  x  400mm
```

# Credits

@aellerton: Forked from @athairus/EDID-Parser-Windows

That version carried this comment:

> Nearly all the code came from this example:
> http://ofekshilon.com/2014/06/19/reading-specific-monitor-dimensions/
>
> A million thanks to this guy!
