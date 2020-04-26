# Makefile for MarkdownMD4C
#

#
# Program specific options:
#
COMPONENT  = MarkdownMD4C
OBJS       = o.md4c \
             o.md4c-html \
             o.entity
EXPORTS    = ${EXP_LIB}.${COMPONENT}.h.md4c \
             ${EXP_LIB}.${COMPONENT}.h.md4c-html \
             ${EXP_LIB}.${COMPONENT}.h.entity

include LibExport

# Exports
${EXP_LIB}.${COMPONENT}.h.md4c: h.md4c
        ${CP} $?  $@  ${CPFLAGS}
${EXP_LIB}.${COMPONENT}.h.md4c-html: h.md4c-html
        ${CP} $?  $@  ${CPFLAGS}
${EXP_LIB}.${COMPONENT}.h.entity: h.entity
        ${CP} $?  $@  ${CPFLAGS}

#---------------------------------------------------------------------------
# Dynamic dependencies:
