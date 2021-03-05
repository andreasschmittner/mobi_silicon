# ToDo List  
for MOBI with Silicon development
- [ ] Si not conserved (decreasing trend)
- [ ] test O_save_carbon_carbonate_depth option: this should be a default calculation with CaCO3
- [ ] check file_names.F:
  - call put_names ('O_sil_dep', 'data/O_sil_dep')
  - call put_names ('O_si_hydr', 'data/O_si_hydr')
do we need those files?
- [ ] check gasbc.F: do we need si as input to co2calc?
- [ ] check global_sums.F: do we need the si stuff?
- [ ] check gosbc.F: O_kk_si_compensating_sources
- [ ] check mom_rest.F: globalsilwflx
- [ ] isotopes
- [ ] inconsistent units: DIC, ALK, O2, Si, OPL in mol/m^3, all other in mmol/m^3
      re-write code so that all tracers use consistent units
- [ ] simplify call of routines: right now many variables are explicitly listed as input/output
      this could be removed by using the corresponding variables from common blocks.
### In Progress

### Completed  
- [x] move calculation of omega out of O_save_carbon_carbonate_chem option
