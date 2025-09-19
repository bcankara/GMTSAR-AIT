# GMTSAR-AIT: GMTSAR Auto Installation Tool

[![DOI](https://joss.theoj.org/papers/10.21105/joss.00000/status.svg)](https://doi.org/10.21105/joss.00000)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

GMTSAR Auto Installation Tool (GMTSAR-AIT) is a lightweight, open‑source automation utility that prepares a fully functional GMTSAR environment on Ubuntu LTS systems with minimal user intervention.

## Overview

GMTSAR is a widely-used open-source software package for processing Interferometric Synthetic Aperture Radar (InSAR) data. However, its manual installation process can be complex and time-consuming, involving intricate package dependencies, compiler requirements, and shell configuration.

GMTSAR-AIT addresses these challenges by:
- Automating system dependency management
- Orchestrating Anaconda setup and environment configuration
- Compiling GMTSAR from source with optimized build parameters
- Performing comprehensive post-installation validation
- Providing detailed error reporting and recovery mechanisms

## Features

- **Automated Installation**: End-to-end automation of GMTSAR setup process
- **Dependency Management**: Intelligent handling of system libraries and packages
- **Environment Configuration**: Automated PATH and library configuration
- **Error Handling**: Comprehensive error detection and reporting
- **Validation System**: Post-installation verification of GMTSAR functionality
- **Modular Architecture**: Clean separation of concerns for maintainability

## System Requirements

- **Operating System**: Ubuntu LTS (18.04, 20.04, 22.04, or newer)
- **Prerequisites**: `git` and `bash` (usually pre-installed)
- **Internet Connection**: Required for downloading dependencies and source code
- **Disk Space**: Minimum 2GB free space for installation
- **Memory**: Minimum 4GB RAM recommended for compilation

## Installation

### Quick Start

1. Clone the repository:
```bash
git clone https://github.com/bcankara/GMTSAR-auto-installation-tool.git
cd GMTSAR-auto-installation-tool
```

2. Copy installation scripts to home directory:
```bash
cp installer.sh gmtsar_setup.sh env_setup.sh ~/
cd ~
```

3. Make the installer executable and run:
```bash
chmod +x installer.sh
bash installer.sh
```

4. Follow the on-screen prompts and wait for completion.

### Post-Installation

After successful installation, ensure your shell configuration is reloaded:
```bash
source ~/.bashrc
# or
source ~/.zshrc  # if using zsh
```

Verify the installation by running:
```bash
which gmtsar
make_inps --help
```

## Usage

Once installed, GMTSAR commands should be available in your shell:

```bash
# Example InSAR processing workflow
make_inps [input_parameters]
csh p2p_processing.csh [configuration_file]
```

For detailed GMTSAR usage instructions, refer to the [official GMTSAR documentation](http://gmt.soest.hawaii.edu/projects/gmt5sar).

## Architecture

GMTSAR-AIT consists of three main components:

1. **`installer.sh`**: Main orchestrator that coordinates the entire installation process
2. **`gmtsar_setup.sh`**: GMTSAR-specific compilation and system integration
3. **`env_setup.sh`**: Environment variable configuration and Conda setup

## Documentation

- [Installation Guide](docs/installation.md) - Detailed installation instructions
- [Troubleshooting](docs/troubleshooting.md) - Common issues and solutions
- [API Reference](docs/api.md) - Script interfaces and configuration options

## Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details on how to submit pull requests, report issues, and contribute to the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Citation

If you use GMTSAR-AIT in your research, please cite:

```bibtex
@article{,
  title={GMTSAR-AIT: Automated preparation of a GMTSAR InSAR processing environment on Ubuntu},
  author={Kara, Burak Can and Demir, Selçuk},
  journal={},
  year={},
  publisher={},
  doi={}
}
```

## Acknowledgments

- GMTSAR developers for providing the foundational InSAR processing software
- Ubuntu and Anaconda communities for robust platform support
- Open-source community for tools and documentation

## Support

For questions, issues, or feature requests:
- **Issues**: [GitHub Issues](https://github.com/bcankara/GMTSAR-auto-installation-tool/issues)
- **Discussions**: [GitHub Discussions](https://github.com/bcankara/GMTSAR-auto-installation-tool/discussions)
- **Email**: burakcan.kara@amasya.edu.tr

## Related Projects

- [GMTSAR](http://gmt.soest.hawaii.edu/projects/gmt5sar) - The core InSAR processing software
- [GMT](https://www.generic-mapping-tools.org/) - Generic Mapping Tools
- [InSAR Scientific Computing Environment](https://github.com/isce-framework/isce2) - Alternative InSAR processing framework

