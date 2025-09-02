// App.jsx
import { Button } from "@/components/ui/button";

export default function App() {
  return (
    <div className="min-h-screen bg-[#0a0a0f] text-white flex flex-col">
      {/* Navbar */}
      <nav className="flex justify-between items-center px-10 py-6">
        <h1 className="text-2xl font-bold">WendoJ.</h1>
        <ul className="flex gap-8 text-gray-300">
          <li className="hover:text-white cursor-pointer">Home</li>
          <li className="hover:text-white cursor-pointer">About</li>
          <li className="hover:text-white cursor-pointer">Projects</li>
          <li className="hover:text-white cursor-pointer">Contact</li>
        </ul>
      </nav>

 {/* Hero Section */}
      <main className="flex flex-1 items-center justify-between px-16">
        {/* Left side */}
        <div className="max-w-lg space-y-6">
          <h2 className="text-5xl font-extrabold leading-snug">
            Hello, I'm <span className="text-blue-500">WendoJ.</span>
          </h2>
          <p className="text-gray-400 text-lg">
            An experienced full-stack developer with a passion for creating
            unique digital experiences.
          </p>
          <Button className="bg-blue-600 hover:bg-blue-700 px-6 py-3 rounded-xl">
            Get in Touch
          </Button>
        </div>

   {/* Right side - illustration */}
        <div className="w-[500px]">
          <img
            src="https://assets-global.website-files.com/63a3c35f4ecbe45cfef95e0d/63a3c35f4ecbe45cfea95e3f_hero-image.svg"
            alt="Abstract Design"
            className="rounded-2xl shadow-2xl"
          />
        </div>
      </main>

{/* Footer */}
      <footer className="text-center py-6 text-gray-500 text-sm">
        © 2025 WendoJ. All rights reserved.
      </footer>
    </div>
  );
}
