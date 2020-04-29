FC = gfortran
#FC = g77

FCFLAGS = -O2
FCFLAGS += -I/usr/include

# libraries needed for linking, unused in the examples
#LDFLAGS = -li_need_this_lib

# List of executables to be built within the package
PROGRAMS = DIFFaX

# "make" builds all
all: $(PROGRAMS)

DIFFaX.o: DIFFaX.inc DIFFaX.par

%: %.o
	$(FC) $(FCFLAGS) -o $@ $^ $(LDFLAGS)

%.o: %.f
	$(FC) $(FCFLAGS) -c $<

# Utility targets
.PHONY: clean veryclean

clean:
	rm -f *.o *.mod *.MOD

veryclean: clean
	rm -f *~ $(PROGRAMS)



