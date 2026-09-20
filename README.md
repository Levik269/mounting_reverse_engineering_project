# Adjustable Angle Camera Mount — Reverse Engineering

Part by part reverse engineering of an AACM (adjustable angle camera mount),
with measured drawings and CAD models for every component.

The original product was fully disassembled part by part and carefully measured
with standard tools such as dial calipers. The measurements were written on
paper as brief sketches showing the real dimensions of each part, and then
transferred to CAD models.

Made in 2025 for a computer aided design course. Modeled in Fusion 360.

## Method

Each part was measured independently, without reference to any original
documentation. Measurements were taken with an analog dial caliper reading to
0.001 in (about 0.025 mm), recorded in inches on hand sketches, and entered
into CAD as measured — no nominal sizes were assumed.

This is visible in the models: the ball post measures 0.7857 in in CAD against
0.786 in on the original sketch, a difference that is only the rounding in
writing the value down.

One dimension does suggest a design intent behind the measurement. The base
outer diameter comes out at 1.2497 in, which is 1 1/4 in to within 0.0002 in.
The remaining dimensions do not land on obvious nominal values, so they are
left as measured.

Threaded features were not measured directly. Thread pitch was identified by
matching the measured major diameter against standard thread series. Threads
are represented as cosmetic features over plain cylindrical geometry, which is
why mated threaded parts overlap in the assembly — the overlap is the thread
engagement, not an interference fit.

Every part was then modeled as a solid, and the parts were assembled to verify
that the reconstructed dimensions are consistent with each other.

## Assembly check

The assembly contains seven components, envelope 63.3 x 50.8 x 57.0 mm. All
seven solids are closed and manifold. No interference is present between any
pair of parts apart from the threaded interfaces described above.

## Parts

| Part | Drawing | STEP | STL |
|---|---|---|---|
| Assembly | [PDF](Assembly/Assembly%20Drawing.pdf) | [STEP](Assembly/Assembly.step) | [STL](Assembly/Assembly.stl) |
| Base | [PDF](Base/Base%20Drawing.pdf) | [STEP](Base/Base.step) | [STL](Base/Base.stl) |
| Base insert | [PDF](Base%20insert/Base%20insert%20Drawing.pdf) | [STEP](Base%20insert/Base%20insert.step) | [STL](Base%20insert/Base%20insert.stl) |
| Housing | [PDF](Housing/Housing%20Drawing.pdf) | [STEP](Housing/Housing.step) | [STL](Housing/Housing.stl) |
| Ball & Post | [PDF](Ball%20%26%20Post/Ball%20%26%20Post%20Drawing.pdf) | [STEP](Ball%20%26%20Post/Ball%20%26%20Post.step) | [STL](Ball%20%26%20Post/Ball%20%26%20Post.stl) |
| Lock wheel | [PDF](lock%20wheel/Lock%20wheel%20Drawing.pdf) | [STEP](lock%20wheel/Lock%20wheel.step) | [STL](lock%20wheel/Lock%20wheel.stl) |
| Hex nut | [PDF](Hex%20nut/Hex%20nut%20Drawing.pdf) | [STEP](Hex%20nut/Hex%20nut.step) | [STL](Hex%20nut/Hex%20nut.stl) |
| Wing Screw | [PDF](Wing%20Screw/Wing%20Screw%20Drawing.pdf) | [STEP](Wing%20Screw/Wing%20Screw.step) | [STL](Wing%20Screw/Wing%20Screw.stl) |

## Files

Each part has its own folder containing three files: a dimensioned drawing as
PDF, the solid model as STEP, and a mesh as STL.

STL files open directly in the browser — GitHub renders them in a 3D viewer,
so any part can be rotated without downloading anything. STEP files carry the
exact solid geometry and open in any CAD system.
