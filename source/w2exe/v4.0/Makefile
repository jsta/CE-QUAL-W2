# http://w2forum.cee.pdx.edu/?q=node/500
# https://www.dropbox.com/sh/xg1c73zglxu8g3m/AACJdxscP_anY3Snmxwxyy1Ta?dl=0

objects = w2modules.o w2_371_gen.o input.o balances.o date.o density.o endsimulation.o gas-transfer.o gate-spill-pipe.o \
	heat-exchange.o hydroinout.o init-cond.o init-geom.o init.o layeraddsub.o \
	macrophyte-aux.o output.o outputa.o outputinit.o restart.o shading.o tdg.o temperature.o \
	time-varying-data.o transport.o update.o az.o \
	water-quality.o waterbody.o withdrawal.o wqconstituents.o 
#FFLAGS = -ffree-line-length-huge -ftrace=full -fzero -c -gstabs+ 
FFLAGS = -c -gstabs+ 
# compiler choices = ifort f95 gfortran
fcompiler = gfortran
cequalw2: $(objects) $(fcompiler) -o cequalw2 $(objects) 
w2modules.o: w2modules.F90 
	$(fcompiler) $(FFLAGS) w2modules.F90 
w2_371_gen.o: w2_371_gen.f90 
	$(fcompiler) $(FFLAGS) w2_371_gen.f90 
input.o: input.f90 
	$(fcompiler) $(FFLAGS) input.f90 
az.o: az.f90 
	$(fcompiler) $(FFLAGS) az.f90 
balances.o: balances.f90 
	$(fcompiler) $(FFLAGS) balances.f90 
date.o: date.f90 
	$(fcompiler) $(FFLAGS) date.f90 
density.o: density.f90 
	$(fcompiler) $(FFLAGS) density.f90 
endsimulation.o: endsimulation.f90 
	$(fcompiler) $(FFLAGS) endsimulation.f90 
gas-transfer.o: gas-transfer.f90 
	$(fcompiler) $(FFLAGS) gas-transfer.f90 
gate-spill-pipe.o: gate-spill-pipe.f90 
	$(fcompiler) $(FFLAGS) gate-spill-pipe.f90 
heat-exchange.o: heat-exchange.f90 
	$(fcompiler) $(FFLAGS) heat-exchange.f90 
hydroinout.o: hydroinout.f90 
	$(fcompiler) $(FFLAGS) hydroinout.f90 
init-cond.o: init-cond.f90 
	$(fcompiler) $(FFLAGS) init-cond.f90 
init-geom.o: init-geom.f90 
	$(fcompiler) $(FFLAGS) init-geom.f90 
init.o: init.f90 
	$(fcompiler) $(FFLAGS) init.f90 
layeraddsub.o: layeraddsub.f90 
	$(fcompiler) $(FFLAGS) layeraddsub.f90 
macrophyte-aux.o: macrophyte-aux.f90 
	$(fcompiler) $(FFLAGS) macrophyte-aux.f90 
output.o: output.f90 
	$(fcompiler) $(FFLAGS) output.f90 
outputa.o: outputa.f90 
	$(fcompiler) $(FFLAGS) outputa.f90 
outputinit.o: outputinit.f90
	$(fcompiler) $(FFLAGS) outputinit.f90 
restart.o: restart.f90 
	$(fcompiler) $(FFLAGS) restart.f90 
shading.o: shading.f90 
	$(fcompiler) $(FFLAGS) shading.f90 
tdg.o: tdg.f90 
	$(fcompiler) $(FFLAGS) tdg.f90 
temperature.o: temperature.f90 
	$(fcompiler) $(FFLAGS) temperature.f90 
time-varying-data.o: time-varying-data.f90 
	$(fcompiler) $(FFLAGS) time-varying-data.f90 
transport.o: transport.f90 
	$(fcompiler) $(FFLAGS) transport.f90 
update.o: update.f90 
	$(fcompiler) $(FFLAGS) update.f90 
water-quality.o: water-quality.f90 
	$(fcompiler) $(FFLAGS) water-quality.f90 
waterbody.o: waterbody.f90 
	$(fcompiler) $(FFLAGS) waterbody.f90 
withdrawal.o: withdrawal.f90 
	$(fcompiler) $(FFLAGS) withdrawal.f90 
wqconstituents.o: wqconstituents.f90 
	$(fcompiler) $(FFLAGS) wqconstituents.f90
