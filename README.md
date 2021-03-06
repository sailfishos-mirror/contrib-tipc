# Transparent Inter-Process Communications (TIPC) Sockets.

TIPC  provides  a  framework  for  inter-process  communication  between
federations of trusted peers that are  cooperating   as  a  unit. It was
developed by Ericsson AB,  as  a   means  to  provide for communications
between Common Control Systems processes and   Network  Element peers in
telephone switching systems, sometimes  operating   at  arm's  length on
different line cards or mainframes. Delegation of responsibility in this
way is one of the fundamental precepts of the Erlang programming system,
also developed at Ericsson. TIPC represents   a more generalized version
of the same behavioral design pattern.

This document was produced using PlDoc,   with  sources found in tipc.pl
and tipc_overview.md.

@author: Jeffrey Rosenwald (JeffRose@acm.org)
@license: BSD-2
@compat: Linux only
