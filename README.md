# AlphaEx
g, 2) = 2 Then ; Include hyphens         ; Hyphens must always occur between alpha characters or apostrophes - on both sides.         $sString = StringRegExpReplace($sString, "([^" &amp; $sAlphaEx &amp; "][-]+)" , " ")         $sString = StringRegExpReplace($sString, "([-]+[^" &amp; $sAlphaEx &amp; "])" , " ")         $sAlphaEx &amp;= "-" ; Add hyphen to the search criteria     EndIf
