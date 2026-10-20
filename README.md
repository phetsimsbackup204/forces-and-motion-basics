Forces and Motion: Basics
=============
"Forces and Motion: Basics" is an educational simulation in HTML5, by <a href="https://phet.colorado.edu/" target="_blank">PhET
Interactive Simulations</a>
at the University of Colorado Boulder. For a description of this simulation, associated resources, and a link to the
published version,
<a href="https://github.com/phetsimsbackup204/forces-and-motion-basics" target="_blank">visit the simulation's web page</a>.

### Try it!

<a href="https://phet-forces-sim.vercel.app/" target="_blank">Click here to
run "Forces and Motion: Basics".</a>

<a href="https://phet-forces-sim.vercel.app/" target="_blank">
<img src="https://raw.githubusercontent.com/phetsimsbackup204/forces-and-motion-basics/main/assets/forces-and-motion-basics-screenshot.png" alt="Screenshot" style="width: 400px;"/>
</a>

### Documentation

The <a href="https://github.com/phetsimsbackup204/phet-info/blob/main/doc/phet-development-overview.md" target="_blank">PhET
Development Overview</a> is the most complete guide to PhET Simulation Development. This guide includes how to obtain
simulation code and its dependencies, notes about architecture & design, how to test and build the sims, as well as
other important information.

### Quick Start

(1) Clone the simulation and its dependencies:

```
git clone https://github.com/phetsimsbackup204/assert.git
git clone https://github.com/phetsimsbackup204/axon.git
git clone https://github.com/phetsimsbackup204/babel.git
git clone https://github.com/phetsimsbackup204/brand.git
git clone https://github.com/phetsimsbackup204/chipper.git
git clone https://github.com/phetsimsbackup204/dot.git
git clone https://github.com/phetsimsbackup204/forces-and-motion-basics.git
git clone https://github.com/phetsimsbackup204/joist.git
git clone https://github.com/phetsimsbackup204/kite.git
git clone https://github.com/phetsimsbackup204/perennial.git perennial-alias
git clone https://github.com/phetsimsbackup204/phet-core.git
git clone https://github.com/phetsimsbackup204/phetcommon.git
git clone https://github.com/phetsimsbackup204/phetmarks.git
git clone https://github.com/phetsimsbackup204/query-string-machine.git
git clone https://github.com/phetsimsbackup204/scenery.git
git clone https://github.com/phetsimsbackup204/scenery-phet.git
git clone https://github.com/phetsimsbackup204/sherpa.git
git clone https://github.com/phetsimsbackup204/sun.git
git clone https://github.com/phetsimsbackup204/tambo.git
git clone https://github.com/phetsimsbackup204/tandem.git
git clone https://github.com/phetsimsbackup204/twixt.git
git clone https://github.com/phetsimsbackup204/utterance-queue.git
```

(2) Install dev dependencies:

```
cd chipper
npm install
cd ../perennial-alias
npm install
cd ../forces-and-motion-basics
npm install
```

(3) Run `grunt dev-server` to start a local development server that will serve the simulation.

(4) Open in the browser: `http://localhost/forces-and-motion-basics/forces-and-motion-basics_en.html`

#### Optional: Build the simulation into a single file

(1) Change directory to the simulation directory: `cd ../forces-and-motion-basics`

(2) Build the sim: `grunt --brands=adapted-from-phet`. It is safe to ignore warnings
like `>> WARNING404: Skipping potentially non-public dependency`, which indicate that non-public PhET-iO code is not
being included in the build.

(3) Open in the
browser: `http://localhost/forces-and-motion-basics/build/adapted-from-phet/forces-and-motion-basics_en_adapted-from-phet.html`

### Get Involved

Join us at the <a href="https://scenerystack.org/community/join/" target="_blank">SceneryStack Community</a>

Help us improve, create a <a href="http://github.com/phetsimsbackup204/forces-and-motion-basics/issues/new" target="_blank">New Issue</a>

### License

See the <a href="https://github.com/phetsimsbackup204/forces-and-motion-basics/blob/main/LICENSE" target="_blank">LICENSE</a>
