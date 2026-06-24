Correções aplicadas:

1. Adicionado `ee_core/src/patches_asm.S`, que estava faltando e causava:
   `No rule to make target 'src/patches_asm.S', needed by 'obj/patches_asm.o'`.

2. Ajustados workflows ps2dev-latest para instalar `build-base`, corrigindo casos de:
   `cc: No such file or directory`.
