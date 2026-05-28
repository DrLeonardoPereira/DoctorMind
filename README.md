![DoctorMind Logo](Logo)

# DoctorMind

import React, { useState } from 'react';

const WelcomeScreen: React.FC = () => {
  const [accepted, setAccepted] = useState(false);

  if (accepted) {
    return null; // ou redirecionar para o jogo
  }

  return (
    <div className="...">
      <img src="IMG-20260413-WA0034.jpg" alt="Logotipo Doctor Mind" />
      <h1>Doctor Mind</h1>
      <h2>Um jogo para exercitar a mente</h2>
      <div className="...">
        <p>Aviso: ...</p>
      </div>
      <button onClick={() => setAccepted(true)}>Aceitar</button>
    </div>
  );
};

export default WelcomeScreen;
