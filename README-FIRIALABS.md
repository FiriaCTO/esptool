A few releases into our project, we started having issues with esptool hanging when we tried
to use the read_flash function.

The issue is not fully understood yet, but sees to be triggered by particular combinations
of FLASH content and block size.

We are creating this fork to support initial work-arounds, and we hope to eventually get to
the root of the issues and create a real fix.
