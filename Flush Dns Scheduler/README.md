# Flushing DNS

## Function : For flushing dns every interval


### example for 5 minutes
`/system scheduler add name="dns Flush" interval=`<strong>"hour:minutes:second"</strong>` on-event="/ip dns cache flush"`


### example for 5 minutes
`/system scheduler add name="dns Flush" interval="00:05:00" on-event="/ip dns cache flush"`

### example for 60 minutes
`/system scheduler add name="dns Flush" interval="01:00:00" on-event="/ip dns cache flush"`

