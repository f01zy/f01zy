```tsx
import { FC } from 'react'

const Folzy:FC = ():JSX.Element => {
  const firstname:String = "Ali"
  const lastname:String = "Aminov"
  const languages: String[] = ["Javascript", "Typescript", "Python", "Php", "scss", "css", "html"]
  const technologies: String[] = ["React", "Node js", "Django", "Disnake", "Axios","Webpack", "Vite"]

  return (
    <>
      <div className="folzy">
        <h1>{firstname}</h1>
        <h1>{lastname}</h1>
        <h2>{languages}</h2>
        <h2>{technologies}</h2>
      </div>
    </>
  )
}

export default Folzy
```
