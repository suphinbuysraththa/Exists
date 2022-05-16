# Exists
MsgBox(0, '', _Reg_Exists('HKEY_CURRENT_USERSoftwareMicrosoftWindowsShellNoRoamMUICache'))    Func _Reg_Exists($sKey)      RegRead($sKey, '')      Return Not (@error > 0)  EndFunc
