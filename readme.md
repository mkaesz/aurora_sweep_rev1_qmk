# aurora_sweep_rev1_qmk

cp /Users/mkaesz/Downloads/aurora_sweep_rev1_de_v1.json /Users/mkaesz/workspace/qmk_home/keyboards/splitkb/aurora/sweep/keymaps/mkaesz/keymap.json

qmk compile -e CONVERT_TO=liatris -kb splitkb/aurora/sweep/rev1 -km mkaesz

cd workspace/qmk_home/

rsync splitkb_aurora_sweep_rev1_mkaesz_liatris.uf2 /Volumes/RPI-RP2/
