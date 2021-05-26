# pds2pdse
Command to convert a PDS to a PDSE with member generations enabled

Syntax: PDS2PDSE from-pds to-pdse MG(nnn) VOL(vol) SWAP

    MG(nnn)   set the maxgen limit
              ** default is the system limit
    VOL(vvv)  volser for the to-pdse
    SWAP      Do renames to swap the datasets after the allocation and copy
   
## Notes

- Requires the PDS command (CBTTape File 182)
