# Japred-Blue
Japred-Blue is simple blue theme

# Installation
User mode install

<p><code>$ chmod a+x INSTALL</p></code>
<p><code>$ ./INSTALL</p></code>

Root mode install 

<p><code>$ su</p></code>
<p><code># chmod a+x INSTALL</p></code>
<p><code># ./INSTALL</p></code>

# Config
* Set metacity align left:
<p><code> gconftool-2 --set /apps/metacity/general/button_layout --type string \\\"close,minimize,maximize:\\\"</p></code>

* Set metacity align right:
<p><code>$ gconftool-2 --set /apps/metacity/general/button_layout --type string \\\":minimize,maximize,close\\\"</p></code>
