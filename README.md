# sc-dumper
frida script (iOS) to dump out old format .scs

# Usage
1) download Frida
2) download patched Brawl Stars .ipa (preferably from here: https://www.mediafire.com/file/cdutfdot1dg1sni/Brawl_Stars58P.ipa/file) (credit to risporce:https://github.com/risporce/Supercell-jailbreak)
3) connect the **jailbroken** iDevice to your computer
4) frida -U -f "com.supercell.laser" -l SupercellSWFdumper.js --runtime=v8
5) find output files in /app_document_path/saved/ 
