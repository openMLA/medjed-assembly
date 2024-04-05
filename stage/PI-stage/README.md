# Physik Instrumente Stage

For development purposes, a PI M-525.2MO stage will be used. It uses small crossed roller bearings and stepper motors (M-229.25S; 10um backlash, 2um repeatability). The Steppers and encoders can be read out via python with the `pipython` python package.

A basic stage is built up around this system.

In the final product a custom replacement for the stage will be required, as it is neither fast enough, nor cheap enough to really serve as a good fit for the Medjed project.