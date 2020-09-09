# Design Ethos

  1. All software, hardware, and designs shall be open source, freely visible to
     anyone.
  2. Anyone with sufficient skill level should be able to tinker, modify, or
     hack on any part of the project, be it in HDL, board layout, firmware, or
     OS.
  3. Modules should be hackable with a moderate level of skill, but still be
     hand assembleable if possible. Ie: TQFP parts are best, BGA need not apply.
  4. The backplane may be more complex as it is necessitated by the higher
     bandwidth design, but it must be open source.
  5. Design first! Everything else is just an artifact.

## Industrial / Mechanical Design Ethos

  1. Designs must be open source!
  2. Designs -> Specifications -> Models
  3. Think 90s retro technical drawings and HUDs.
  4. If an action by the hacker would break the machine, design it such that it
     is at the very least difficult to do so accomplish (ie: registration pins
     to prevent backwards insertions).
  5. 3D printing is king, FDM is the process.
  6. Print-in-place is nice, but bolts are better.
  7. 130° is the angle measure, and the angle measure is 130°.
  8. The Cube is 150mm x 150mm x 150mm. No less, no more.
  9. Retrofuturistic is the future we all wanted.

## Software Design Ethos

  1. Open source is king! Everything is GPLv2, including firmware, and buildable
     using OSS tooling.
  2. Open data is queen! Use sane, open formats as much as is possible. Ie:
     PBM + Deflate for icons, because it's just text!
  3. Hackable! If existing tooling works, let's use it. If existing tooling is
     brain-damaged or painful to work with, redesign!
  4. Design docs first! Code is an artifact of the design, not the design
     itself.
  5. Performance and efficiency. Software must not be bloated, and designed with
     size, performance, and simplicity in mind! We are engineers, not code
     monkeys!
  6. No engineer is an island -- prototype, get review and sign off on a design
     before writing code!

## Hardware Design Ethos

  1. All BOM parts should be repeatably sourced from well known distributors
     from Digikey, Mouser, Arrow, etc. or from the OEMs themselves. Parts from
     Alibaba or Amazon need not apply!
  2. All BOM parts must not be EOL -- if it's marked as "not recommended for new
     designs", it need not apply!
  3. Hand-assembleable modules! TQFP-144, 0603 is the smallest we get.
