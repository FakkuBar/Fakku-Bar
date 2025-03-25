import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import Image from "next/image";

export default function FakkuBarEvent() {
  return (
    <div className="bg-gray-900 text-white min-h-screen">
      {/* Header */}
      <header className="bg-black py-4 px-6 flex justify-between items-center">
        <h1 className="text-xl font-bold">FAKKU BAR</h1>
        <nav>
          <ul className="flex space-x-6">
            <li><a href="#" className="hover:text-gray-400">Home</a></li>
            <li><a href="#" className="hover:text-gray-400">Programação</a></li>
            <li><a href="#" className="hover:text-gray-400">Fotos</a></li>
            <li><a href="#" className="hover:text-gray-400">Eventos</a></li>
            <li><a href="#" className="hover:text-gray-400">Contato</a></li>
          </ul>
        </nav>
      </header>
      
      {/* Banner do evento */}
      <div className="relative w-full h-[500px]">
        <Image src="/evento-fakku.jpg" layout="fill" objectFit="cover" alt="Banner do evento" />
        <div className="absolute inset-0 bg-black bg-opacity-50 flex flex-col items-center justify-center text-center p-6">
          <h2 className="text-5xl font-bold text-yellow-500">FAKKU VIBE</h2>
          <p className="text-2xl">Sexta, 12 de Abril - 22:00</p>
          <p className="text-lg mt-2">Com MC Paiva, Baomi e DJ Nathi</p>
          <Button className="mt-4 bg-yellow-500 text-black px-6 py-3 font-bold">Garanta seu ingresso</Button>
        </div>
      </div>
      
      {/* Informações adicionais */}
      <section className="p-8 text-center">
        <h3 className="text-3xl font-bold mb-4">O melhor evento da cidade</h3>
        <p className="text-lg max-w-3xl mx-auto">
          Curta uma noite inesquecível no Fakku Bar com os maiores nomes da música e um ambiente sofisticado.
        </p>
      </section>
    </div>
  );
}
