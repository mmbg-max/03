# 03
const floatParticles = [];
const burstParticles = [];
for (let i = 0; i < FLOAT_COUNT; i++) {
const p = new Particle(
Math.random() * width, Math.random() * height, "float");
