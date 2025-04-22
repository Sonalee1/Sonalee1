// Sonali's Personal Portfolio Website
import React from 'react';
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";

export default function Portfolio() {
  return (
    <div className="min-h-screen bg-gradient-to-br from-white to-rose-100 p-6">
      <header className="text-center py-10">
        <h1 className="text-4xl font-bold text-pink-700">Sonali Bhosale</h1>
        <p className="text-lg mt-2 text-gray-700">AI + STEM Educator | Music Technologist | Creative Learning Advocate</p>
      </header>

      <section className="grid gap-6 md:grid-cols-2 lg:grid-cols-3">
        <Card>
          <CardContent>
            <h2 className="text-xl font-semibold text-pink-600">🌟 About Me</h2>
            <p className="mt-2 text-gray-600">
              I'm an educator and technologist blending AI, STEM, and music to create magical learning experiences.
              With over 5 years of experience in teaching, robotics, and creative tech, I love designing workshops
              that spark innovation through art and science.
            </p>
          </CardContent>
        </Card>

        <Card>
          <CardContent>
            <h2 className="text-xl font-semibold text-pink-600">🎤 Passion Projects</h2>
            <ul className="mt-2 list-disc pl-5 text-gray-600">
              <li>AI Music Lab – Emotions to melodies with Google Magenta</li>
              <li>VoiceBot with Personality – A Dialogflow bot that sings and talks</li>
              <li>Workshops: Singing with STEM & The Science of Sound</li>
            </ul>
          </CardContent>
        </Card>

        <Card>
          <CardContent>
            <h2 className="text-xl font-semibold text-pink-600">📚 Teaching & Mentorship</h2>
            <p className="mt-2 text-gray-600">
              I’ve mentored students on AI and robotics projects, from building humanoids to developing AI-based
              recognition systems. I design inclusive STEM+Arts programs to make tech more human and joyful.
            </p>
          </CardContent>
        </Card>

        <Card>
          <CardContent>
            <h2 className="text-xl font-semibold text-pink-600">📂 Resume & Downloads</h2>
            <p className="mt-2 text-gray-600">View or download my resume and cover letter tailored for creative education roles.</p>
            <div className="mt-4 space-x-4">
              <Button variant="outline" asChild>
                <a href="/Sonali_Bhosale_Resume_Music_Education_Google.docx" download>Download Resume</a>
              </Button>
              <Button variant="outline" asChild>
                <a href="/Sonali_Bhosale_Cover_Letter_Music_Education_Google.docx" download>Download Cover Letter</a>
              </Button>
            </div>
          </CardContent>
        </Card>

        <Card>
          <CardContent>
            <h2 className="text-xl font-semibold text-pink-600">🔗 Connect With Me</h2>
            <p className="mt-2 text-gray-600">Follow my journey, explore my projects, or collaborate with me:</p>
            <ul className="mt-2 list-disc pl-5 text-blue-600">
              <li><a href="https://www.linkedin.com/in/sonali-bhosale" target="_blank">LinkedIn</a></li>
              <li><a href="mailto:mailsbhosle@gmail.com">Email</a></li>
            </ul>
          </CardContent>
        </Card>
      </section>
    </div>
  );
}
