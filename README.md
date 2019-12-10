# M2 travis configuration

## Installation

`composer require skywire/travis --dev`

Commit new files to git.

Files can be customised for your project, composer should not overwrite them when you run an install or update

## Usage

Travis file covers unit, integration and api-functional tests. If you are not using any of these suites in your project then you can remove them from the matrix. Each matrix entry launches a travis instance, so it's best to only use the suites you require.
