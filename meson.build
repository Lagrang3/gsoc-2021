project('GSoC proposal')

latex=find_program('rubber')

docfiles = [
    'gsoc.tex','intro.tex','biblio.bib','info.tex',
    'state.tex', 'proposal.tex',
    'schedule.tex','app_ring.tex']

custom_target('doc',
    build_by_default: true,
    output : 'gsoc.pdf',
    input : docfiles,
    command : [latex,'--pdf','--into=@OUTDIR@','@INPUT0@'])
