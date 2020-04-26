# Makefile for MarkdownMD4C
#

#
# Program specific options:
#
COMPONENT  = MarkdownMD4C
OBJS       = o.md4c
EXPORTS    = ${EXP_LIB}.${COMPONENT}.h.md4c

include LibExport

# Exports
${EXP_LIB}.${COMPONENT}.h.md4c: h.md4c
        ${CP} $?  $@  ${CPFLAGS}

#---------------------------------------------------------------------------
# Dynamic dependencies:
