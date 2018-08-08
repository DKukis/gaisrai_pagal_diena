# gaisrai_pagal_diena
Bandymas webscrapinti gaisrų ir gelbėjimo darbų duomenis iš "http://www.vpgt.lt/vpgt/m/m_events_summary/wfiles/e_"+data+".htm"

Problema:
---------------------------------------------------------------------------
AttributeError                            Traceback (most recent call last)
<ipython-input-3-27c6b1948056> in <module>()
     13         for td in cols:
     14             text1 = td.find('p')
---> 15             data0.append(text1.text)
     16 
     17     data.append(data0)

AttributeError: 'NoneType' object has no attribute 'text'
---------------------------------------------------------------------------

negaliu sukurti kelių dienų duomenis nuskaitančio ciklo, nes meta klaidą. Ką daryt?
