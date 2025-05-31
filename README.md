<h1 align="center">👋 LinguaLink</h1>

<p align="center">
  <i>
    Revolutionizing Sign Language Communication with Cutting-Edge Real-Time Translation Models.
    <br>
    Enjoy seamless Sign Language Translation on desktop and mobile.
  </i>
</p>


## Key Features

```
┌─────────────────────┐
│Spoken Language Audio│                                                              ┌─────────┐
└─────────┬───────────┘                                                  ┌──────────►│Human GAN│
          │                                                              │           └─────────┘
          ▼                                                              │
┌────────────────────┐     ┌───────────────┐     ┌───────────┐    ┌──────┴──────┐    ┌───────────────┐
│Spoken Language Text├────►│Normalized Text├────►│SignWriting├───►│Pose Sequence├───►│Skeleton Viewer│
└─────────┬──────────┘     └───────────────┘     └───────────┘    └──────┬──────┘    └───────────────┘
          │                        ▲                   ▲                 │
          ▼                        │                   │                 │           ┌─────────┐
┌───────────────────────┐          │                   │                 └──────────►│3D Avatar│
│Language Identification├──────────┘───────────────────┘                             └─────────┘
└───────────────────────┘
```

### [Sign Language Translation
```
┌──────────────────────────┐                                ┌────────────────────┐
│Upload Sign Language Video│                      ┌────────►│Spoken Language Text│
└──────────┬───────────────┘                      │         └──────────┬─────────┘
           │                                      │                    │
           │          ┌────────────┐       ┌──────┴────┐               │
           ├─────────►│Segmentation├──────►│SignWriting│               │
           │          └────────────┘       └───────────┘               │
           │                                                           ▼
┌──────────┴────────────────┐                               ┌─────────────────────┐
│Camera Sign Language Video │                               │Spoken Language Audio│
└───────────────────────────┘                               └─────────────────────┘
```

### Want to Help?

## Development

### Prerequisites

- Install [Node.js] which includes [Node Package Manager][npm]

### Setting Up the Project

Install dependencies locally:

```bash
npm install
```

Run the application:

```bash
npm start
```

Test the application:

```bash
npm test
```

