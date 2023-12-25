Pull request creation failed. Validation failed: was submitted too quickly  



* Draft PR

Fixes some of https://github.com/UniversalDependencies/docs/issues/265#event-9295022119

I assume for all of these correction that it is offset by 1? (train starts from 0 rather than 1).

- [ ] 2: acl:relcl for non-relative clause
- [x] 4: acl:relcl for parenthetical (should be parataxis)
- [x] 5: nmod -> appos

I assume this if the "socialdemokratiske". I am uncertain about this one if someone could explain why that is the case that would be wonderful.

- [ ] 6, 50: conj attached to cc instead of first conj

6: It does not seem like conj is attached to cc but rather amod?
50: 

- [ ] 7: garbled; wrong root (parataxis); wrong compound:prt; wrong mwe

I am not sure how to understand this one:
root --> parataxis
compound:prt --> advmod (my best guess)
can't find the mwe?

- [ ] 11: nmod attached to verb particle
- [x] 18: For otte miljoner = cc -> nmod
- [ ] 19: et eller andet - missad coordination

missed coordination? Couldn't find anything on missad

- [ ] 20: Alene i Hamburg; ophobet skrab
- [ ] 21: wrong root (parataxis); ud = nmod -> compound:prt; nmod attached to particle
- [ ] 28: garbled; main clause treated as xcomp
- [ ] 29: garbled: dels på - dels på
- [ ] 30: wrong structure for "Berlingske Tidendes afslag"; nmod:tmod -> advmod

Couldn't find this in the data. Only `nmod:poss`, might still be an error though.

- [ ] 39, 41: wrong root (expl)
- [x] 43: skyldige = amod -> nmod [bug]
- [ ] 44: wrong root [clausal predicate with copula] + parenthetical and punctuation wrong attachment [bug]
- [ ] 50: garbled; conditional treated as coordination