---
scapolite:
    class: collection
    version: '0.51'
    lang: en
    format: md
id: Windows_Server_2019_STIG
id_namespace: mil.disa
version: '001.003'
status: accepted
title: Windows Server 2019 Security Technical Implementation Guide
notice: <see below>
objectives: <see below>
applicability:
  - system: https://scap.nist.gov/schema/cpe/2.3
    cpes:
      - cpe:/o:microsoft:windows_server_2019:-
contents:
  - class: group_ref
    idref: V-92961
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000028-GPOS-00009
  - class: group_ref
    idref: V-92963
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000297-GPOS-00115
  - class: group_ref
    idref: V-92965
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000297-GPOS-00115
  - class: group_ref
    idref: V-92967
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000032-GPOS-00013
  - class: group_ref
    idref: V-92969
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000032-GPOS-00013
  - class: group_ref
    idref: V-92971
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000033-GPOS-00014
  - class: group_ref
    idref: V-92973
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000033-GPOS-00014
  - class: group_ref
    idref: V-92979
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000004-GPOS-00004
  - class: group_ref
    idref: V-92981
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000004-GPOS-00004
  - class: group_ref
    idref: V-92983
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000004-GPOS-00004
  - class: group_ref
    idref: V-92987
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000240-GPOS-00090
  - class: group_ref
    idref: V-92989
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000240-GPOS-00090
  - class: group_ref
    idref: V-92991
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-92995
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-92997
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-92999
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-93001
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-93003
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-93005
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-93007
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-93009
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-93011
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-93013
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-93015
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-93017
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-93029
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93039
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93041
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93045
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93047
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93049
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93051
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93053
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93055
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93057
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93059
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93061
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93063
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93065
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93067
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93069
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93071
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93073
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93075
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93077
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93079
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93081
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93083
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93085
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93087
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-93089
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93091
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93093
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93095
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93097
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93099
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93101
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93103
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93105
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93107
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93109
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93111
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93113
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93115
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93117
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93119
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93133
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93135
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93137
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93139
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-93141
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000021-GPOS-00005
  - class: group_ref
    idref: V-93143
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000021-GPOS-00005
  - class: group_ref
    idref: V-93145
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000329-GPOS-00128
  - class: group_ref
    idref: V-93151
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000062-GPOS-00031
  - class: group_ref
    idref: V-93153
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000470-GPOS-00214
  - class: group_ref
    idref: V-93155
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000470-GPOS-00214
  - class: group_ref
    idref: V-93161
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000470-GPOS-00214
  - class: group_ref
    idref: V-93163
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000470-GPOS-00214
  - class: group_ref
    idref: V-93165
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000470-GPOS-00214
  - class: group_ref
    idref: V-93171
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000472-GPOS-00217
  - class: group_ref
    idref: V-93173
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000042-GPOS-00020
  - class: group_ref
    idref: V-93175
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000042-GPOS-00020
  - class: group_ref
    idref: V-93177
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000341-GPOS-00132
  - class: group_ref
    idref: V-93179
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000341-GPOS-00132
  - class: group_ref
    idref: V-93181
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000341-GPOS-00132
  - class: group_ref
    idref: V-93189
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000057-GPOS-00027
  - class: group_ref
    idref: V-93191
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000057-GPOS-00027
  - class: group_ref
    idref: V-93193
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000057-GPOS-00027
  - class: group_ref
    idref: V-93195
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000257-GPOS-00098
  - class: group_ref
    idref: V-93197
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000057-GPOS-00027
  - class: group_ref
    idref: V-93199
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000362-GPOS-00149
  - class: group_ref
    idref: V-93201
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000362-GPOS-00149
  - class: group_ref
    idref: V-93215
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93221
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93233
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93235
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93237
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93239
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93241
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93243
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93249
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93251
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93253
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93255
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93257
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93259
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93261
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93263
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93265
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93267
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93269
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00229
  - class: group_ref
    idref: V-93273
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93275
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93279
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93281
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93283
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93285
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93287
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93291
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93293
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93295
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93297
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93299
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93301
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93303
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93305
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93307
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93309
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-93373
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000368-GPOS-00154
  - class: group_ref
    idref: V-93375
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000368-GPOS-00154
  - class: group_ref
    idref: V-93377
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000368-GPOS-00154
  - class: group_ref
    idref: V-93383
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93385
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93387
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93389
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93391
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93393
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93395
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93397
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93399
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93401
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93403
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93405
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93407
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93409
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93411
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93413
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93415
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93419
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-93421
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000096-GPOS-00050
  - class: group_ref
    idref: V-93423
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000096-GPOS-00050
  - class: group_ref
    idref: V-93425
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000373-GPOS-00157
  - class: group_ref
    idref: V-93427
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000373-GPOS-00157
  - class: group_ref
    idref: V-93429
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000373-GPOS-00157
  - class: group_ref
    idref: V-93431
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000373-GPOS-00157
  - class: group_ref
    idref: V-93433
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000373-GPOS-00157
  - class: group_ref
    idref: V-93435
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000373-GPOS-00157
  - class: group_ref
    idref: V-93443
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000112-GPOS-00057
  - class: group_ref
    idref: V-93445
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000112-GPOS-00057
  - class: group_ref
    idref: V-93447
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000112-GPOS-00057
  - class: group_ref
    idref: V-93449
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000112-GPOS-00057
  - class: group_ref
    idref: V-93451
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000112-GPOS-00057
  - class: group_ref
    idref: V-93453
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000379-GPOS-00164
  - class: group_ref
    idref: V-93455
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000379-GPOS-00164
  - class: group_ref
    idref: V-93459
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000069-GPOS-00037
  - class: group_ref
    idref: V-93463
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000078-GPOS-00046
  - class: group_ref
    idref: V-93465
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000073-GPOS-00041
  - class: group_ref
    idref: V-93467
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000073-GPOS-00041
  - class: group_ref
    idref: V-93469
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000074-GPOS-00042
  - class: group_ref
    idref: V-93471
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000075-GPOS-00043
  - class: group_ref
    idref: V-93477
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000076-GPOS-00044
  - class: group_ref
    idref: V-93479
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000077-GPOS-00045
  - class: group_ref
    idref: V-93487
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000066-GPOS-00034
  - class: group_ref
    idref: V-93489
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000066-GPOS-00034
  - class: group_ref
    idref: V-93491
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000066-GPOS-00034
  - class: group_ref
    idref: V-93493
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000067-GPOS-00035
  - class: group_ref
    idref: V-93495
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000120-GPOS-00061
  - class: group_ref
    idref: V-93497
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000121-GPOS-00062
  - class: group_ref
    idref: V-93499
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000393-GPOS-00173
  - class: group_ref
    idref: V-93501
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000393-GPOS-00173
  - class: group_ref
    idref: V-93503
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000125-GPOS-00065
  - class: group_ref
    idref: V-93505
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000125-GPOS-00065
  - class: group_ref
    idref: V-93507
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000125-GPOS-00065
  - class: group_ref
    idref: V-93511
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000478-GPOS-00223
  - class: group_ref
    idref: V-93517
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000134-GPOS-00068
  - class: group_ref
    idref: V-93519
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000134-GPOS-00068
  - class: group_ref
    idref: V-93521
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000134-GPOS-00068
  - class: group_ref
    idref: V-93523
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000134-GPOS-00068
  - class: group_ref
    idref: V-93525
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000134-GPOS-00068
  - class: group_ref
    idref: V-93527
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000134-GPOS-00068
  - class: group_ref
    idref: V-93529
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000134-GPOS-00068
  - class: group_ref
    idref: V-93533
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000138-GPOS-00069
  - class: group_ref
    idref: V-93537
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000138-GPOS-00069
  - class: group_ref
    idref: V-93539
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000138-GPOS-00069
  - class: group_ref
    idref: V-93541
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000420-GPOS-00186
  - class: group_ref
    idref: V-93545
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-93547
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-93549
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-93551
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-93553
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-93555
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-93557
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-93559
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-93561
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-93563
    idref_namespace: mil.disa.Windows-Server-2019-STIG
    ref_comment: SRG-OS-000433-GPOS-00192
profiles:
  - class: profile_ref
    idref: MAC-1_Classified
    idref_namespace: mil.disa.Windows-Server-2019-STIG
  - class: profile_ref
    idref: MAC-1_Public
    idref_namespace: mil.disa.Windows-Server-2019-STIG
  - class: profile_ref
    idref: MAC-1_Sensitive
    idref_namespace: mil.disa.Windows-Server-2019-STIG
  - class: profile_ref
    idref: MAC-2_Classified
    idref_namespace: mil.disa.Windows-Server-2019-STIG
  - class: profile_ref
    idref: MAC-2_Public
    idref_namespace: mil.disa.Windows-Server-2019-STIG
  - class: profile_ref
    idref: MAC-2_Sensitive
    idref_namespace: mil.disa.Windows-Server-2019-STIG
  - class: profile_ref
    idref: MAC-3_Classified
    idref_namespace: mil.disa.Windows-Server-2019-STIG
  - class: profile_ref
    idref: MAC-3_Public
    idref_namespace: mil.disa.Windows-Server-2019-STIG
  - class: profile_ref
    idref: MAC-3_Sensitive
    idref_namespace: mil.disa.Windows-Server-2019-STIG
  - class: profile_ref
    idref: Disable_Slow_Rules
    idref_namespace: mil.disa.Windows-Server-2019-STIG
  - class: profile_ref
    idref: CAT_I_Only
    idref_namespace: mil.disa.Windows-Server-2019-STIG
values:
  - id: winrm_client_allow_unencrypted_traffic_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: 'WinRM Client: Allow unencrypted traffic'
    description: 'WinRM Client: Allow unencrypted traffic'
    type: number
    default: disabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: turn_on_basic_feed_authentication_over_http_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Turn on Basic feed authentication over HTTP
    description: Turn on Basic feed authentication over HTTP
    type: number
    default: disabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: turn_off_shell_protocol_protected_mode_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Turn off shell protocol protected mode
    description: Turn off shell protocol protected mode
    type: number
    default: disabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: turn_off_program_inventory_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Turn off program inventory
    description: This policy controls the state of the Program Inventory collector
        in the system.
    type: number
    default: enabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: turn_off_printing_over_http_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Turn off printing over HTTP
    description: 'Computer Configuration\Administrative Templates\System\Internet
        Communication Management\Internet Communication settings: Turn off printing
        over HTTP.'
    type: number
    default: enabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: turn_off_heap_termination_corruption_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Turn off Heap termination on corruption
    description: Turn off Heap termination on corruption
    type: number
    default: disabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: turn_off_downloading_of_print_drivers_over_http_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Turn off downloading of print drivers over HTTP
    description: 'Computer Configuration\Administrative Templates\System\Internet
        Communication Management\Internet Communication settings: Turn off downloading
        of print drivers over HTTP.'
    type: number
    default: enabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: turn_off_data_execution_prevention_for_explorer_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: turn_off_data_execution_prevention_for_explorer
    description: turn_off_data_execution_prevention_for_explorer
    type: number
    default: disabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: turn_off_autoplay_for_non_volume_devices_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: turn_off_autoplay_for_non_volume_devices
    description: This policy setting determines whether autoplay is enabled for non
        volume devices.
    type: number
    default: enabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: set_client_connection_encryption_level_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Set client connection encryption level
    description: Set client connection encryption level
    type: number
    default: high_level
    operator: equals
    definitions:
      - selector: low_level
        value: 1
      - selector: client_compatible
        value: 2
      - selector: high_level
        value: 3
  - id: require_secure_rpc_communication_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Require secure RPC communication
    description: Require secure RPC communication
    type: number
    default: enabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: require_a_password_when_a_computer_wakes_plugged_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Require a Password when a Computer Wakes (Plugged)
    description: 'Computer Configuration\Administrative Templates\System\Power Management:
        Sleep Settings - Require a Password when a Computer Wakes (Plugged).'
    type: number
    default: enabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: require_a_password_when_a_computer_wakes_on_battery_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Require a Password when a Computer Wakes (On Battery)
    description: 'Computer Configuration\Administrative Templates\System\Power Management:
        Sleep Settings - Require a Password when a Computer Wakes (On Battery).'
    type: number
    default: enabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: prevent_internet_explorer_security_prompt_for_windows_installer_scripts_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Prevent Internet Explorer security prompt for Windows Installer scriptsr
    description: Prevent Internet Explorer security prompt for Windows Installer scripts
    type: number
    default: disabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: prevent_downloading_of_enclosures_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Prevent downloading of enclosures
    description: Prevent downloading of enclosures
    type: number
    default: enabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: password_reversible_encryption_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Enforce Reversible Encryption When Storing Passwords
    description: This value determines whether Windows Server 2016 is configured to
        prevent passwords from being stored using a two-way hash. 1 = enabled
    type: boolean
    default: disabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: password_minimum_length_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Minimum Password Length
    description: The minimum number of characters required for a password
    type: number
    default: 14_characters
    operator: greater than or equal
    definitions:
      - selector: 8_characters
        value: 8
      - selector: 9_characters
        value: 9
      - selector: 12_characters
        value: 12
      - selector: 14_characters
        value: 14
      - selector: 15_characters
        value: 15
  - id: password_minimum_age_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Minimum Password Age
    description: The minimum age in seconds before a password may be changed. 1 day
        = 86400 seconds
    type: number
    default: 86400_seconds
    operator: greater than or equal
    definitions:
      - selector: 86400_seconds
        value: 86400
      - selector: 172800_seconds
        value: 172800
      - selector: 432000_seconds
        value: 432000
  - id: password_maximum_age_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Maximum Password Age
    description: The maximum age in seconds before a password expires. (90 days =
        7776000 seconds; 60 days = 5184000)
    type: number
    default: 5184000_seconds
    operator: less than or equal
    definitions:
      - selector: 5184000_seconds
        value: 5184000
      - selector: 7776000_seconds
        value: 7776000
  - id: password_enforce_history_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Enforce Password History
    description: The number of passwords remembered
    type: number
    default: 24_passwords
    operator: greater than or equal
    definitions:
      - selector: 5_passwords
        value: 5
      - selector: 24_passwords
        value: 24
  - id: password_complexity_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Enforce Password Complexity
    description: This value determines whether Windows 7 implements a minimum level
        of strong password filtering. 1 = enabled
    type: boolean
    default: enabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: no_name_release_on_demand_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: 'MSS: (NoNameReleaseOnDemand) Allow computer to ignore NetBIOS name release
        requests except from WINS servers'
    description: 'MSS: (NoNameReleaseOnDemand) Allow computer to ignore NetBIOS name
        release requests except from WINS servers'
    type: number
    default: enabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: maximum_system_log_size_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Maximum System Log Size
    description: The value defines the maximum size (in KB) of the system log.
    type: number
    default: enabled:32768_kb
    operator: equals
    definitions:
      - selector: enabled:16384_kb
        value: 16384
      - selector: enabled:32768_kb
        value: 32768
      - selector: enabled:81920_kb
        value: 81920
  - id: maximum_security_log_size_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Maximum Security Log Size
    description: The value defines the maximum size (in KB) of the security log.
    type: number
    default: enabled:196608_kb
    operator: equals
    definitions:
      - selector: enabled:49152_kb
        value: 49152
      - selector: enabled:98304_kb
        value: 98304
      - selector: enabled:196608_kb
        value: 196608
  - id: maximum_application_log_size_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Maximum Application Log Size
    description: The value defines the maximum size (in KB) of the application log.
    type: number
    default: enabled:32768_kb
    operator: equals
    definitions:
      - selector: enabled:16384_kb
        value: 16384
      - selector: enabled:32768_kb
        value: 32768
      - selector: enabled:81920_kb
        value: 81920
  - id: limit_blank_password_use_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: 'Accounts: Limit local account use to blank passwords to console logon
        only'
    description: This value defines the desired status of limiting the use of blank
        passwords. 1 = enabled; 0= disabled
    type: number
    default: enabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: ip_source_routing_protection_level_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: 'MSS: (DisableIPSourceRouting) IP source routing protection level (protects
        against packet spoofing)'
    description: IP source routing is a mechanism that allows the sender to determine
        the IP route that a datagram should take through the network. Microsoft recommends
        to configure this setting to Not Defined for enterprise environments and to
        Highest Protection for high security environments to completely disable source
        routing. HKLM\System\CurrentControlSet\Services\Tcpip\Parameters\DisableIPSourceRouting
    type: number
    default: source_routing_packets_disabled
    operator: equals
    definitions:
      - selector: source_routing_packets_allowed
        value: 0
      - selector: source_routing_packets_ignored
        value: 1
      - selector: source_routing_packets_disabled
        value: 2
  - id: guest_account_status_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Status of Guest Account
    description: This value defines the desired status of the built-in Guest account.
        0 = disabled; 1 = enabled.
    type: boolean
    default: disabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: enumerate_administrator_accounts_on_elevation_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Enumerate administrator accounts on elevation
    description: 'Computer Configuration\Administrative Templates\Windows Components\Credential
        User Interface: Enumerate administrator accounts on elevation.'
    type: number
    default: disabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: do_not_allow_passwords_to_be_saved_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Do not allow passwords to be saved
    description: Do not allow passwords to be saved
    type: number
    default: enabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: do_not_allow_drive_redirection_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Do not allow drive redirection
    description: Do not allow drive redirection
    type: number
    default: enabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: default_behavior_for_autorun_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: default_behavior_for_autorun
    description: default_behavior_for_autorun
    type: number
    default: do_not_execute_autorun_commands
    operator: equals
    definitions:
      - selector: do_not_execute_autorun_commands
        value: 1
      - selector: automatically_execute_autorun_commands
        value: 2
  - id: always_prompt_for_password_upon_connection_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Always prompt for password upon connection
    description: Always prompt for password upon connection
    type: number
    default: enabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: allow_user_control_over_installs_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Allow user control over installs
    description: Allow user control over installs
    type: number
    default: disabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: allow_icmp_redirects_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: 'MSS: (EnableICMPRedirect) Allow ICMP redirects to override OSPF generated
        routes'
    description: Internet Control Message Protocol (ICMP) redirects cause the stack
        to plumb host routes. These routes override the Open Shortest Path First (OSPF)generated
        routes, attackers can use source routed packets to conceal the address of
        their computer. HKLM\System\CurrentControlSet\Services\Tcpip\Parameters\EnableICMPRedirect
    type: number
    default: disabled
    operator: equals
    definitions:
      - selector: disabled
        value: 0
      - selector: enabled
        value: 1
  - id: account_lockout_threshold_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Account Lockout Threshold
    description: The maximum number of failed attempts that can occur before the account
        is locked out
    type: number
    default: 3_attempts
    operator: less than or equal
    definitions:
      - selector: 3_attempts
        value: 3
      - selector: 5_attempts
        value: 5
      - selector: 10_attempts
        value: 10
      - selector: 50_attempts
        value: 50
  - id: account_lockout_reset_counter_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: Reset Account Lockout Counter After
    description: The time period in seconds to be used with the lockout threshold
        value. For example, if the threshold is set to 10 attempts and the duration
        is set to 15 minutes, then if more than 10 failed login attempts occur with
        a single user account within a 15-minute period, the account will be disabled.
        15 minutes = 900 seconds
    type: number
    default: 900_seconds
    operator: greater than or equal
    definitions:
      - selector: 900_seconds
        value: 900
      - selector: 3600_seconds
        value: 3600
      - selector: 86400_seconds
        value: 86400
  - id: MSS_IPv6_source_routing_protection_level_var
    id_namespace: mil.disa.Windows-Server-2019-STIG
    title: 'MSS: (DisableIPSourceRouting IPv6) IP source routing protection level
        (protects against packet spoofing)'
    description: Allowing source routed network traffic allows attackers to obscure
        their identity and location.
    type: number
    default: Highest_protection
    operator: equals
    definitions:
      - selector: No_additional_protection
        value: 0
      - selector: Medium_protection
        value: 1
      - selector: Highest_protection
        value: 2
history:
  - version: '001.003'
    date: '2020-05-15'
    action: created
    short_description: accepted
    internal_comment: ''
---


## /notice

      

## /objectives

This Security Technical Implementation Guide is published as a tool to improve the security of Department of Defense (DoD) information systems. The requirements are derived from the National Institute of Standards and Technology (NIST) 800-53 and related documents. Comments or proposed revisions to this document should be sent via email to the following address: disa.stig_spt@mail.mil.
