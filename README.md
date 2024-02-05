This is a [Next.js](https://nextjs.org/) + [FastApi](https://fastapi.tiangolo.com/) project 
## Getting Started

First, Create python environment for Fast Api 

Using conda create
```bash
conda create --name <name> python=<py version> 
conda create --name fast-next python=3.11 
```

# Then
```bash
pip install fastapi
pip install uvicorn
pip install httpie
```

To run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
This will concurrently Start both Fast Api and nextjs 

Open [http://localhost:3000](http://localhost:3000) in your browser to see Frontend (NEXTJS)
# And
Open [http://localhost:3000/api/status](http://localhost:3000/api/status) in your browser to see Backend Status(FASTAPI) 
