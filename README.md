# tagIServiceProvider-
#include &lt;Constants.au3>  Opt("MustDeclareVars", True)  If @OSVersion &lt;> "WIN_10" Then Exit MsgBox($MB_SYSTEMMODAL, "", "This script only runs on Win 10")  ; Instanciation objects Local $CLSID_ImmersiveShell = "{c2f03a33-21f5-47fa-b4bb-156362a2f239}" Local $IID_IUnknown = "{00000000-0000-0000-c000-000000000046}" Local $IID_IServiceProvider = "{6D5140C1-7436-11CE-8034-00AA006009FA}" Local $tIID_IServiceProvider = __uuidof($IID_IServiceProvider) Local $tagIServiceProvider  = _     "QueryService hresult(struct*;struct*;ptr*);"
