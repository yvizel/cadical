add_library (cadical_src OBJECT analyze.cpp
arena.cpp
assume.cpp
averages.cpp
backtrack.cpp
backward.cpp
bins.cpp
block.cpp
ccadical.cpp
checker.cpp
clause.cpp
collect.cpp
compact.cpp
condition.cpp
config.cpp
constrain.cpp
contract.cpp
cover.cpp
decide.cpp
decompose.cpp
deduplicate.cpp
drattracer.cpp
elim.cpp
ema.cpp
extend.cpp
external.cpp
external_propagate.cpp
file.cpp
flags.cpp
flip.cpp
format.cpp
frattracer.cpp
gates.cpp
idruptracer.cpp
instantiate.cpp
internal.cpp
ipasir.cpp
lidruptracer.cpp
limit.cpp
logging.cpp
lookahead.cpp
lratbuilder.cpp
lratchecker.cpp
lrattracer.cpp
lucky.cpp
message.cpp
minimize.cpp
occs.cpp
options.cpp
parse.cpp
phases.cpp
probe.cpp
profile.cpp
proof.cpp
propagate.cpp
queue.cpp
random.cpp
reap.cpp
reduce.cpp
rephase.cpp
report.cpp
resources.cpp
restart.cpp
restore.cpp
score.cpp
shrink.cpp
signal.cpp
solution.cpp
solver.cpp
stats.cpp
subsume.cpp
terminal.cpp
ternary.cpp
transred.cpp
util.cpp
var.cpp
veripbtracer.cpp
version.cpp
vivify.cpp
walk.cpp
watch.cpp)

install (FILES *.h DESTINATION include/cadical)
