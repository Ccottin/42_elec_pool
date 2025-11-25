
# ˚. ✧̣̇.⋆˳.✦ .˚    Bill Of Materials    ˚. ✦.˳⋆.✧̣̇. ˚


| Reference     | Qty | Value         | DNP | Exclude from BOM | Exclude from Board | Footprint                              | Datasheet | Unit Price | Ext Price |
|--------------|-----|---------------|-----|-------------------|---------------------|-----------------------------------------|-----------|------------|-----------|
| C1,C3,C4     | 3   | 100nF         |     |                   |                     | 42_footprint:Capacitor_100nf           |           | 0.0024     | 0.0072    |
| C2           | 1   | 1uF           |     |                   |                     | 42_footprint:Capacitor_1uf             |           | 0.0049     | 0.0049    |
| C5,C6        | 2   | 12pF          |     |                   |                     | 42_footprint:Capacitor_12pf            |           | 0.0048     | 0.0048    |
| D1           | 1   | Green         |     |                   |                     | 42_footprint:Led_Green                 |           | 0.0081     | 0.0081    |
| D2           | 1   | Red           |     |                   |                     | 42_footprint:Led_Red                   |           | 0.0032     | 0.0032    |
| J1,J2        | 2   | ~             |     |                   |                     | 42_footprint:Connector_12_2.54pitch    |           |            |           |
| J3           | 1   | FTDI          |     |                   |                     | 42_footprint:Connector_6_2.54pitch     |           |            |           |
| R1,R3        | 2   | 10K           |     |                   |                     | 42_footprint:Resistance_10k            |           | 0.0011     | 0.0011    |
| R2           | 1   | 330           |     |                   |                     | 42_footprint:Resistance_330            |           | 0.0011     | 0.0011    |
| SW1          | 1   | ~             |     |                   |                     | 42_footprint:Switch                    |           | 0.1189     | 0.1189    |
| U1           | 1   | Atmega328P-A  |     |                   |                     | 42_footprint:Atmega328p-au             |           | 1.6088     | 1.6088    |
| Y1           | 1   | 16MHz         |     |                   |                     | 42_footprint:Crystal Oscillator        |           | 0.0662     | 0.0662    |


# ˚. ✧̣̇.⋆˳.✦ .˚  Pin Layout   ˚. ✦.˳⋆.✧̣̇. ˚


     +----------------------------+
     | [ ]D9               D10[ ] |  
     | [ ]D8     +---+     D11[ ] |  
     | [ ]D7    -| U |-    D12[ ] |   
     | [ ]D6    -| N |-    D13[ ] |   
     | [ ]D5    -| I |-     A0[ ] |   
     | [ ]D4    -| C |-     A1[ ] |   
     | [ ]D3    -| O |-     A2[ ] |
     | [ ]D2    -| R |-     A3[ ] |   
     | [ ]GND   -| N |-     5V[ ] |   
     | [ ]RST    +---+     RST[ ] |   
     | [ ]RXI              GND[ ] |  
     | [ ]TXO              RAW[ ] | 
     |                            | 
     |  GND GND RAW RXI TXO DTR   | 
     |  [ ] [ ] [ ] [ ] [ ] [ ]   |
     \____________________________/
      

  
  
  
  
  
Credits : https://busyducks.com/ascii-art-arduino-pinouts/